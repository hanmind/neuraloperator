# Neural Operator
I'm studying how to make models learn ``parametric partial differential equations`` by ``Neural Operators``. After learning **Fourier Neural Operator(FNO)** and **Physics-Informed Neural Operator(PINO)** etc., we're going to go on our own study using them. Wait a bit please!

## Files
Most of the files are based on Zongyi-Li's work. We focused on understanding FNO and **visuallizing model results**. You can check how effective FNO is by viewing them. 
* ``fourier_1d_Burgers.py`` is the Fourier Neural Operator for 1D problem such as the (time-independent) Burgers equation discussed in Section 5.1 in the paper. The neural operator maps the solution function from time 0 to time 1. We added some meaningful graphs and the animation of predicted flow.
* ``fourier_2d_Darcy.py`` is the Fourier Neural Operator for 2D problem such as the Darcy Flow discussed in Section 5.2 in the paper. The neural operator maps from the coefficient function to the solution function. **It'll be updated soon.**

## For More Information on Neural Operator
https://zongyi-li.github.io/neural-operator/
