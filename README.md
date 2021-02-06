# SModelWrap [![PyPI version](https://badge.fury.io/py/SModelWrap.svg)](https://badge.fury.io/py/SModelWrap) [![Build Status](https://travis-ci.com/SrzStephen/ModelWrap.svg?branch=main)](https://travis-ci.com/SrzStephen/ModelWrap)
## You probably should not use this
I had to quickly create something and upload it to pypy so that I could get something working properly with an
 AWS Sagemaker pipeline that I don't own.
 
## What is it
Provides the class ```ModelPerClass``` which implements a custom predict method that will allow predictions on a single model 
per unique value in a row of a pandas DataFrame.
