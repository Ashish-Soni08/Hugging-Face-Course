---
id: kwj49qpqqfcvrjfi5qg7h89
title: VirtualEnvironments
desc: ''
updated: 1656277971419
created: 1656277907874
---

When running a Python command in your terminal, such as python --version, you should think of the program running your command as the “main” Python on your system. We recommend keeping this main installation free of any packages, and using it to create separate environments for each application you work on — this way, each application can have its own dependencies and packages, and you won’t need to worry about potential compatibility issues with other applications.

In Python this is done with virtual environments, which are self-contained directory trees that each contain a Python installation with a particular Python version alongside all the packages the application needs. Creating such a virtual environment can be done with a number of different tools, but we’ll use the official Python package for that purpose, which is called venv

First, create the directory you’d like your application to live in — for example, you might want to make a new directory called transformers-course at the root of your home directory:

mkdir ~/transformers-course
cd ~/transformers-course