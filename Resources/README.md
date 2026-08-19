# Week 1: Introduction

# 🗃️ Datasets útiles

| Título | Tarea | Data format | Link |
|---|---|---|---|
| Fruits dataset | Clasificación | ```.csv``` | [Clean](https://drive.google.com/file/d/1M8tiAWDZclABJN1Meq9oEHCLJTNyHdpP/view)
| Malaria cells | Clasificación | ```.png``` | [Raw](https://drive.google.com/file/d/1tCa6MHRUM34pv0wwDBsRkpFqMIZPk6iO/view?usp=drive_link)
| Noisy captchas | Clasificación | ```.png``` | [Raw](https://drive.google.com/file/d/1EyZiqMovGI0lZ_uawxAOoGcKm9CBy0kM/view?usp=drive_link)
| Disease diagnosis | Clasificación | ```.csv``` | [Raw](https://drive.google.com/file/d/1T-n-AoJ_As36oBLjY9Frc6NP_PwXWzTq/view?usp=sharing), [Clean](https://drive.google.com/file/d/1Sp_u1vaTafdrvUsZQHzGRCmcy4VfDf_s/view?usp=sharing)
| Houses in Iowa | Regresión | ```.csv``` | [Clean](https://drive.google.com/file/d/1BnTVOkFwRxT0wTKdfkbKF26R4iEKKshJ/view?usp=sharing)
| Natural images | Regresión | ```.png``` | [Raw](https://drive.google.com/file/d/1hF7a-tBXWm9efkG8yi5T-Yh58V2F5icH/view?usp=drive_link)
| Heart stroke dataset | Regresión | ```.csv``` | [Raw](https://drive.google.com/file/d/1JNtrwHJukzeK6l5ljvUgB8_8yESZ_qDK/view?usp=drive_link)
| Bank Customer segmentation | Clasificación / Clustering  | ```.csv``` | [Raw](https://drive.google.com/file/d/1omMtaPEQRilZzTRYqBM5VXU5oXl2BMG9/view?usp=sharing), [Clean](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing)
| Product recommendation| Clasificación / Clustering  | ```.csv``` | [Raw](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing), [Clean](https://drive.google.com/file/d/14V61wky2xXsYwD62EdOfv0AJvH89MG0F/view?usp=sharing)



# 🗃️ Paquetes y librerías


## Docker environment
A preconfigured environment has been provided to ensure that all code runs with the correct dependencies. This helps maintain reproducibility and avoids issues related to package versions or system configuration. To use this environment, you must first install Docker. You can follow the official installation guide here: 

[https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)

Once Docker is installed, download the container image by running the following command:

```docker pull rubenfonnegra/jupyter-ml-docker```

After downloading the image, you can start the container with:

```docker run -p 8888:8888 jupyter-ml-docker```

This command will launch a JupyterLab instance accessible from your browser. From there, you can upload the notebook files and execute the code within the prepared environment. Once the container is running, open the URL shown in the terminal to open your browser and navigate through the files. 


## Python libraries

* [SciPy](http://www.scipy.org/): scientific, mathematical, and engineering package for Python
* [scikit-learn](http://scikit-learn.org/): machine learning Scipy add-on
* [Kaggle](https://www.kaggle.com/): datascience competition, many interesting data sets and different competitions with prizes.
* [TensorFlow](https://www.tensorflow.org/): open source software library for dataflow and differentiable programming across a range of tasks.
* [PyTorch](https://pytorch.org/): open source machine learning library based on the Torch library.
* [Keras](https://keras.io/): high-level neural networks API, written in Python and capable of running on top of TensorFlow, PyTorch, or Jax.
* [MLTools](https://drive.google.com/file/d/18Y834Tvtj_-Px9yNmbAB4yV4L0gcIZ20/view?usp=sharing): high-level python library with helper functions for machine learning.  


# Referencias


* [Alp14] Alpaydin, E. [Introduction to Machine Learning](https://faculty.ozyegin.edu.tr/ethemalpaydin/books/), 3Ed. The MIT Press, 2014
* [Bis24] Bishop, C. M. & Bishop H, [Deep Learning: Foundations and Principles](https://www.bishopbook.com/), Springer, 2024.
* [Mur12] Murphy, Kevin P. [Machine learning: a probabilistic perspective](https://probml.github.io/pml-book/). The MIT Press, 2012. 
* [Sha14] Shalev-Shwartz, S., & Ben-David, S. (2014). [Understanding machine learning: From theory to algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf). Cambridge university press.
* [Dei20] Deisenroth, M. P., Faisal, A. A., & Ong, C. S. (2020). [Mathematics for machine learning](https://mml-book.github.io/). Cambridge University Press.
<!-- * [Bar13] Barber, David, [Bayesian Reasoning and Machine Learning](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.HomePage), Cambridge University Press, 2013. -->
* [Bis06] Bishop, C.  [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf). Springer-Verlag, 2006
<!-- * [HTF09] Hastie, T. and Tibshirani, R. and Friedman.  [The elements of statistical learning: data mining, inference, and prediction](http://statweb.stanford.edu/~tibs/ElemStatLearn/), Springer, 2009 -->
* [GBC16] Goodfellow, Ian, Yoshua Bengio, and Aaron Courville. [Deep learning](https://www.deeplearningbook.org/). MIT press, 2016.
* [DHS00] Duda, R. O., Hart, P. E., and Stork, D. G. 2000 Pattern Classification (2nd Edition). Wiley-Interscience.
* [SC04] Shawe-Taylor, J. and Cristianini, N. 2004 Kernel Methods for Pattern Analysis. Cambridge University Press.
* [SS02] Scholkopf, B. and Smola, A.J., 2002, Learning with kernels, MIT Press.


## Cursos complementarios

* [Coursera Machine Learning Course](https://www.coursera.org/learn/machine-learning): one of the first (and still one of the best) machine learning MOOCs taught by Andrew Ng.
* [MIT-IntroDL] <a href= "http://introtodeeplearning.com">MIT 6.S191 Introduction to Deep Learning</a>, Spring 2025,  MIT
* [IAI-Udac] [Intro to Artificial Intelligence](https://www.udacity.com/course/intro-to-artificial-intelligence--cs271), Udacity
