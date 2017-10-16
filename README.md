# gpuRNN

Although there are many neural network implementations either directly
written in R, such as [nnet](https://CRAN.R-project.org/package=nnet) and 
[neuralnet](https://CRAN.R-project.org/package=neuralnet), and linked to
other frameworks, such as [keras](https://CRAN.R-project.org/package=keras)
and [tensorflow](https://CRAN.R-project.org/package=tensorflow), there is 
no package that readily allows much flexibility in developing new neural 
network models without needing to go to other languages or interfaces.

This package is intended to provide R a neural network (or deep learning)
framework to allow R users a means to not only build and train networks but
to also allow users to more rapidly contribute novel methods and approaches
in the R language.

To make this package performant, it is based on the [gpuR](https://CRAN.R-project.org/package=gpuR) package to allow users
to leverage GPUs.  However, it is my intent to not make this a strict
requirement.

