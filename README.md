# PID 101 for Robotics

The proportional-integral-derivative (PID) control structure is widely used, but often not well understood.  Many also tune their controllers by trial-and-error, which is also not ideal.  This short tutorial series of notebooks—with examples written in Python—is intended to provide an brief and systematic introduction to PID control.  Practitioners in robotics are the intended audience, although the concepts are applicable more broadly.

## Part I: Basics

The first notebook (Part I) provides a hands-on introduction to the feedback control of simple single-input, single-output (SISO) systems.  What is perhaps unique about this notebook is that we introduce PID control solely in the time domain (i.e., without reliance on Laplace domain techniques), which is arguably more intuitive.

### Main File(s)

* [PID-101-Part1.ipynb](PID-101-Part1.ipynb) (Jupyter notebook)

## Part II: Tuning

The second notebook (to come) will introduce a few practical ways for choosing PID gains (i.e., _tuning_) that work especially well for robotics applications.

## About the Author

[Joshua A. Marshall](https://www.ece.queensu.ca/people/J-Marshall/), PhD, PEng  
[Ingenuity Labs Research Institute](https://ingenuitylabs.queensu.ca)  
Queen's University  
Mitchell Hall, Room 395  
Kingston, ON K7L 3N6 Canada  

## License

Source code examples in this notebook are subject to an [MIT License](LICENSE).
