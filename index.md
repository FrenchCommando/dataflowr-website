# Deep Learning Do It Yourself!

\blurb{
    This site collects resources to learn Deep Learning in the form of
    Modules available through the sidebar on the left.
    As a student, you can walk through the modules at your own pace and
    interact with others thanks to the associated [Discord server](https://discord.gg/nZQ3fe3). You don’t need any special hardware or software.
}

## Practical deep learning course

The main goal of the course is to allow students to understand papers, blog posts and codes available online and to adapt them to their projects as soon as possible. In particular, we avoid the use of any high-level neural networks API and focus on the [PyTorch](https://pytorch.org/) library in Python.

The course is divided into sessions (containing possibly several modules), each session requiring a significant amount of coding. At the end of this course, students were able to read very recent papers and reproduce (or even ameliorate) their experiments. 

All the code used in this course is available on the GitHub repository [dataflowr/notebooks](https://github.com/dataflowr/notebooks). You will find the solutions to the practicals on this repo! You can fork the repo if you want to run the code locally: [GitHub Docs about fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) then follow the steps in [Module 0](./modules/0-sotfware-installation/). Most of the code will not require a GPU. 

:warning: When a GPU is required , you can launch the code on colab by following the corresponding link given in the module (see for example [Module 1](./modules/1-intro-general-overview/)).

Pre-requisites:

- Mathematics: basics of linear algebra, probability, differential calculus and optimization
- Programming: Python. Test your proficiency: [quiz](https://dataflowr.github.io/quiz/python.html)

### :sunflower: Session 1

Start right away and train a deep neural network on a GPU with [Module 1 - Introduction & General Overview](./modules/1-intro-general-overview/)

Be sure to build your own classifier with more dogs and cats in the practicals.
~~~
<details>
  <summary>Things to remember</summary>
~~~
> - you do not need to understand everything to run a deep learning model! But the main goal of this course will be to come back to each step done today and understand them...
> - to use the dataloader from Pytorch, you need to follow the API (i.e. for classification store your dataset in folders)
> - using a pretrained model and modifying it to adapt it to a similar task is easy. 
> - if you do not understand why we take this loss, that's fine, we'll cover that in Module 3.
> - even with a GPU, avoid unnecessary computations!
~~~
</details>
~~~

### :sunflower: Session 2

TBA
## Curators

[Marc Lelarge](https://www.di.ens.fr/~lelarge/),  [Andrei Bursuc](https://abursuc.github.io/) with [Jill-Jênn Vie](https://jill-jenn.net/)

## Course in a hurry


**Super fast track** to learn the basics of deep learning from scratch:
- Have a look at the [slides](https://dataflowr.github.io/slides/module1.html) of [Module 1: Introduction & General Overview](./modules/1-intro-general-overview)
- Run the [notebook](https://github.com/dataflowr/notebooks/blob/master/Module2/02a_basics.ipynb) (or in [colab](https://colab.research.google.com/github/dataflowr/notebooks/blob/master/Module2/02a_basics.ipynb)) of [Module 2a: Pytorch Tensors](./modules/2a-pytorch-tensors)
- Run the [notebook](https://github.com/dataflowr/notebooks/blob/master/Module2/02b_linear_reg.ipynb) (or in [colab](https://colab.research.google.com/github/dataflowr/notebooks/blob/master/Module2/02b_linear_reg.ipynb)) of [Module 2b: Automatic Differentiation](./modules/2b-automatic-differentiation)
- Check the [Minimal working examples](./modules/3-loss-functions-for-classification/#minimal_working_examples) of [Module 3: Loss functions for classification](./modules/3-loss-functions-for-classification). If you do not understand, have a look at the [slides](https://dataflowr.github.io/slides/module3.html).
- Have a look at the [slides](https://dataflowr.github.io/slides/module4.html) of [Module 4: Optimization for Deep Learning](./modules/4-optimization-for-deep-learning)
- Try playback speed 1.5 for the [video](https://youtu.be/OiyZXdnLHcI?t=149) from [Module 5: Stacking layers](./modules/5-stacking-layers).
- Run the [notebook](https://github.com/dataflowr/notebooks/blob/master/Module6/06_convolution_digit_recognizer.ipynb) (or in [colab](https://colab.research.google.com/github/dataflowr/notebooks/blob/master/Module6/06_convolution_digit_recognizer.ipynb)) of [Module 6: Convolutional Neural Network](./modules/6-convolutional-neural-network)
- Try playback speed 2 for the [video](https://youtu.be/vm-ZusIUkiY?t=133) from [Module 7: Dataloading](./modules/7-dataloading)
- Have a look at the [slides](https://dataflowr.github.io/slides/module8a.html) of [Module 8a: Embedding layers](./modules/8a-embedding-layers)
- Well done! Now you have time to enjoy deep learning!

<!-- ### Annotation tool

- [hypothes.is](https://hypothes.is/groups/EzzjE8gb/deep-learning-ens-2020) allows you to annotate this website and the web in general. You'll find some hints for the practicals here!
-->


## For contributors

Join the [GitHub repo dataflowr](https://github.com/dataflowr) and make a pull request. [What are pull requests?](https://yangsu.github.io/pull-request-tutorial/)

Thanks to [Daniel Huynh](https://github.com/dhuynh95), [Eric Daoud](https://github.com/ericdaat), [Simon Coste](https://github.com/SimonCoste)
<!-- to be updated
## Modules

- [Module 0: Software installation](./modules/0-sotfware-installation)
- [Module 1: Introduction & General Overview](./modules/1-intro-general-overview)
- [Module 2a: Pytorch Tensors](./modules/2a-pytorch-tensors)
- [Module 2b: Automatic Differentiation](./modules/2b-automatic-differentiation)
- [Module 3: Loss functions for classification](./modules/3-loss-functions-for-classification)
- [Module 4: Optimization for Deep Learning](./modules/4-optimization-for-deep-learning)
- [Module 5: Stacking layers](./modules/5-stacking-layers)
- [Module 6: Convolutional Neural Network](./modules/6-convolutional-neural-network)
- [Module 7a: Embedding layers and dataloaders](./modules/7a-embedding-layers-dataloaders)
- [Module 7b: Collaborative Filtering](./modules/7b-collaborative-filtering)
- [Modules 8: Autoencoders](./modules/8-autoencoders)
- [Module 9: Generative Adversarial Networks](./modules/9-generative-adversarial-networks)
- [Module 10a: Recurrent Neural Networks theory](./modules/10a-recurrent-neural-networks-theory)
- [Module 10b: Recurrent Neural Networks practice](./modules/10b-recurrent-neural-networks-practice)
-->


Materials from this site is used for courses at ENS and X. 

~~~
<img src="/assets/ENS_logo.jpg" style="width: 400px; height: auto; display: inline">
<img src="/assets/X_logo.png" style="margin-left:1em; width: 180px; height: auto; display: inline">
~~~
