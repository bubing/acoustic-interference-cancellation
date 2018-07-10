Echo Cancellation
======

# Introduction
This is the GitHub page for Speech Signal Echo Cancellation, which is one of the projects in the summer internship.<br>
The program consists of:<br>
* Room echo creation
* Double-talk detector using Geigel algorithm
* NLMS adaptive filer
* Non-linear processor
* Echo Return Loss Enhancement (ERLE) calculation

The main contributor to this project is:<br>
`Zhuowen Lin`<br>
The programming language is MATLAB. 
The nomenclature of the variables in the program follows the nomenclature in the instruction article [*Implementation of an Acoustic Echo Canceller Using Matlab*](http://scholarcommons.usf.edu/cgi/viewcontent.cgi?article=2452&context=etd)

# Logs
## 2018/7/3
* Get basic knowledge about echo cancellation by reading an instruction atricle [*Implementation of an Acoustic Echo Canceller Using Matlab*](http://scholarcommons.usf.edu/cgi/viewcontent.cgi?article=2452&context=etd)
* Configure the git repository
## 2018/7/4
* Code the program main_function.m
* Read a paper [*Acoustic Echo Cancellation Using NLMS-Neural Network Structures*](https://pdfs.semanticscholar.org/de48/88dc9cca6eef62563940b931a66da43a22b2.pdf)
## 2018/7/5
* Read a paper [*Multiple-input neural network-based residual echo suppression*](https://hal.inria.fr/hal-01723630/file/CARBAJAL_ICASSP_2018.pdf)
* Read a paper [*Multilayer Adaptation Based Complex Echo Cancellation And Voice Enhancement*](https://m.media-amazon.com/images/G/01/amazon.jobs/JunYang_ICASSP2018._CB1520904270_.pdf)
* Get the raw acoustic data from mentor
## 2018/7/6
* Read a paper [*Multi-Microphone Acoustic Echo Cancellation using Relative Echo Transfer Functions*](https://www.researchgate.net/publication/321792298_Multi-Microphone_acoustic_echo_cancellation_using_relative_echo_transfer_functions)
* Collect two other papers in realm of the new echo cancellation model
## 2018/7/9
* Read an instruction article [*Adaptive Noise Cancellation*](http://www.cs.cmu.edu/~aarti/pubs/ANC.pdf). Build a new model for adaptive interference cancellation (AIC).
* Download the AIC demo program from [*DSP ALGORITHM*](https://www.dspalgorithms.com/www/aic/aic.php). Test it on the raw acoustic data.
* Try several possible versions of AIC MATLAB code.
## 2018/7/10
* Read the the second chapter and several example programs about echo cancellation in [*User Manual of The Adaptive Signal Processing Toolbox*](https://www.dspalgorithms.com/www/aspt/maspt/aspt.html)
* Create a mind map about how this project is conducted.