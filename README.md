# Advanced Safety Filter

The project includes Jupyter notebooks that model and simulate the concept of an advanced safety filter.

* [2_power_converter_case_study_unconstraint](https://github.com/MichaelSchneeberger/advanced-safety-filter/blob/main/jupyter/2_power_converter_case_study_unconstraint.ipynb)
* [3_power_converter_case_study](https://github.com/MichaelSchneeberger/advanced-safety-filter/blob/main/jupyter/3_power_converter_case_study.ipynb)
* [4_power_converter_case_study_iqref](https://github.com/MichaelSchneeberger/advanced-safety-filter/blob/main/jupyter/4_power_converter_case_study_iqref.ipynb)
* [5_simulations](https://github.com/MichaelSchneeberger/advanced-safety-filter/blob/main/jupyter/5_simulations.ipynb)



## How to run Jupyter Notebooks

Install Python 3.12 and Jupyterlab.

Then, clone this project to your local machine and install the requirements using pip:

```
pip install -r requirements.txt
```

Next, open the Jupyter notebooks using Jupyterlab.


## References

Here are some references relevant to this project:

* The paper [Control Barrier Functions: Theory and Applications](https://arxiv.org/pdf/1903.11199) introduces the concept of a safety filter.
* The paper [Sums Of Sqaures, Moment Matrices And Optimization Over Polynomials](https://homepages.cwi.nl/~monique/files/moment-ima-update-new.pdf) provides a comprehensive introduction to SOS optimization.
* The youtube playlist [A Course on LMIs in Systems and Control](https://www.youtube.com/playlist?list=PL5ebyVGQORm6n158o-I_liUZ7Q5Od43li) offers an accessible introduction to SOS optimization.
* [SOSOpt](https://github.com/MichaelSchneeberger/sosopt) is a Python library designed for solving sums-of-squares (SOS) optimization problems.
* [PolyMat](https://github.com/MichaelSchneeberger/sosmap) is a Python library designed for the representation and manipulation of multivariate polynomial matrices.


## Citing
```
@article{schneeberger2024advanced,
  title={Advanced safety filter based on SOS Control Barrier and Lyapunov Functions},
  author={Schneeberger, Michael and Mastellone, Silvia and D{\"o}rfler, Florian},
  journal={arXiv preprint arXiv:2401.06901},
  year={2024}
}
```