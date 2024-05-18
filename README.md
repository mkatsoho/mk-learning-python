# mk-learning-python
This introduces a learning path for python3. I really encorage self-learning. 

NOTE: Learn python3 rather than python2, which is out of date.

## Two learning methods
- Learn from easy to complex.

Learning easy tutorial first, then junior tutorial, finally advanced one.

- Example oriented learning.
  
For a section, try examples first and understand how & why. After that read other long chatty words.

## Tutorials

1) w3school

- English tutorial - https://www.w3schools.com/python/python_intro.asp
- Chinese tutorial - https://www.w3school.com.cn/python/index.asp

2) Cheat Sheet
   
The w3chool one is still a bit long, use this cheat sheet to wrap up.
- English cheat sheet - https://learnxinyminutes.com/docs/python/
- Chinese cheat sheet - https://learnxinyminutes.com/docs/zh-cn/python-cn/

3) Junior level books
- English Book: [Head First Python 3rd Editon](https://www.oreilly.com/library/view/head-first-python/9781492051282)
- Chinese Book: [Head First Python 中文版 第二版](https://spu.jd.com/10957017.html)


4) Python for machine learning (not cover Neural Network)
- Engilsh book: TBD
- Chinese book: [李烨 机器学习极简入门](https://m.bookschina.com/8702521.htm) (本书较难买到，可以去国家图书馆借阅)
   
5) Python for Deep Learning

   TBD, suggest to read books or video tutorials about Pytorch

## Suggested IDE

- for a beginner (with access to google): [colab web IDE](https://colab.research.google.com/) 
- for a multi-language open-source-oriented programmer: [vscode community edition](https://visualstudio.microsoft.com/vs/community/)
- for a multi-language programmer: [vscode](https://code.visualstudio.com/)
- for a none programmer: [pycharm](https://www.jetbrains.com/pycharm/download/)
- for a person to learn python for deep learning: [colab web IDE with free/non-free GPUs](https://colab.research.google.com/)

## Suggested practices (from easy to hard)
1) direct coding

   write codes to read .csv file and write to another .csv file (use basic file read/write functions, or use numpy functions for large volume data)

2) use functions

   rewrite 1), orgnize codes as functions, use cmdline parameters (e.g. input_file, output_file, etc) for reading/writing files, or make it woke like linux pipeline command
   
3) try machine learning

   use limited dataset to do linear regression, logestic regression, refer to books about machine learning. Mostly leveaging scilearn (SKLearn) liberary.
   
4) use a out-of-box deep learning model for a business casehttps://racket-lang.org/

   the goal is to use a model to achieve your business goal. Details are TBD.

5) Use the out-of-box model in 4), retrain it using your data

   retrain a out-of-box model, to make it suitable for your business data. Use the new model for your business case. This model should be more accurate/suitable then the 4) model. Unforturnately, a beginer's new model most likely is not as good as the 4) model. Tuning hyperparameters to improve your model's quality.

6) create your own model of machine learning

  beyond reusing a out-of-box model, create your own model and then train it to meet your business case. I suggest pytorch in all kinds of solutions. I hope I can give more details in this summer for your reference.

  ## Beyond python

  You are quit familar with python now and want to make a break through. Let's try functional programming (FP) rather than object oriented programming (OOP). A few suggested next-step functional programming langusages:

  - [racket](https://racket-lang.org/) easy to learn, but not suitable for business. A recomended start-point for your learning
  - [clojure](https://clojure.org/) a modern FP language, suitable for business, based on Java Virtual Machine (JVM)
  - [elixir](https://elixir-lang.org/) a modern FP language on top of Erlang (a ultra-old FP language), suitable for concurrent business, based on BEAM virtual machine

```
In short, JVM is the base runtime of Java and quite a few moden languages. if
you heard the slogon "running anywhere", these words give a positive comments
to JVM instead of Java. JVM can run on all kinds of Operation Systems and/or
hardware.

BEAM:
The virtual machine on which both Elixir and Erlang run. BEAM is specifically
designed for running concurrent and distributed systems, making it highly suitable
for telecommunications, messaging systems, and other applications requiring high
availability and reliability.

JVM:
The virtual machine on which Java and other JVM languages (like Scala, Kotlin,
 and Clojure) run. The JVM is optimized for running object-oriented languages
and provides features like automatic memory management and platform independence.
```

  
