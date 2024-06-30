# KHNN
Keras-based Hypercomplex Neural Networks

Authors: Radoslaw A. Kycia, Agnieszka Niemczynowicz

Description: This package ralizes general hypercomplex algebras neural networks. Dense and Convolutional (1D, 2D, 3D) hypercomplex layers are included. The package works with:
- Keras + TensorFlow (Dense, Convolutional 1D, Convolutional 2D, Convolutional 3D)
- Keras + PyTorch (Dense, Convolutional 2D - experimental implementations with TensorFlow channels alignement and PyTorch data alignement)
Package contains:
- Examples - direcotry contains Jupyter Notebooks illustrating some example usage of classes
- Makefile - simple makefile to run some basic tests and to generate documentation


Usage: The simplest way to use the package is to copy all the Python files in your working direcotry and import them.

Documentation: you can create HTML documentation by running 'make generate_doc'. The HTML files are in doc directory that will be autmatically crreated. Additional examples are in 'Examples' directory.

Acknowledgements: This KHNN library has been supported by the [Polish National Agency for Academic Exchange](http://nawa.gov.pl/) Strategic Partnership Programme under Grant No. BPI/PST/2021/1/00031 [nawa.gov.pl](http://nawa.gov.pl/).

Disclaimer: This library was created with the high standards. However it requires some knowledgde of neural networks and advanced mathematics to be used. It is given 'as if'. We try to test it in various situations, however, we are not responsible for all damages that can occure during the usage of the package.

We plan to develop this software, so if you want to help us, please do not hesitate to contact us.
