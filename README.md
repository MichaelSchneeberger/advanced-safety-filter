# Advanced Safety Filter

A safety filter is a technique from *control theory* to render an well-established controller safe within the limits of a dynamical system.
The advanced safety filter additionally guarantees non-inference during nominal operation, thereby preserving the original behavior of the controller during nominal conditions.
This toolbox computes *Control Barrier and Lyapunov Functions* based on *Sum-of-Squares* Optimization, which can then be integrated into the traditional safety filter through a *Quadratic Program* formulation.
The projects is structured as follows:

 - jupyter - A [*Jupyter* notebook template](https://github.com/MichaelSchneeberger/advanced-safety-filter/blob/main/jupyter/advanced_safety_filter_template.ipynb) for computing the optimized parameters of an advanced safety filter.
 - jupyter/power_converter_case_study - *Jupyter* notebooks demonstrating the application of the template in a power converter case study.
 - tex - *LaTeX* files of the corresponding research paper.


## How to run Jupyter Notebooks

Install Python 3.12 and Jupyterlab.

Then, clone this project to your local machine and install the requirements using pip:

```
pip install -r requirements.txt
```

Next, open the Jupyter notebook template using Jupyterlab.


## Citing
```
@article{schneeberger2024advanced,
  title={Advanced safety filter based on SOS Control Barrier and Lyapunov Functions},
  author={Schneeberger, Michael and Mastellone, Silvia and D{\"o}rfler, Florian},
  journal={arXiv preprint arXiv:2401.06901},
  year={2024}
}
```


## References

Here are some references relevant to this project:

* The paper [Control Barrier Functions: Theory and Applications](https://arxiv.org/pdf/1903.11199) introduces the concept of a safety filter.
* The paper [Sums Of Sqaures, Moment Matrices And Optimization Over Polynomials](https://homepages.cwi.nl/~monique/files/moment-ima-update-new.pdf) provides a comprehensive introduction to SOS optimization.
* The youtube playlist [A Course on LMIs in Systems and Control](https://www.youtube.com/playlist?list=PL5ebyVGQORm6n158o-I_liUZ7Q5Od43li) offers an accessible introduction to SOS optimization.
* [SOSOpt](https://github.com/MichaelSchneeberger/sosopt) is a Python library designed for solving sums-of-squares (SOS) optimization problems.
* [PolyMat](https://github.com/MichaelSchneeberger/sosmap) is a Python library designed for the representation and manipulation of multivariate polynomial matrices.
