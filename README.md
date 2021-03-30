# Model Training Script Specification

## Motivation

During the development of [TinyMS](https://github.com/tinyms-ai/tinyms), we found that in order to have a greatly abstracted high level deep learning APIs it is vital that the scripts in ModelZoo are formatted in a standardized way.

However since the state of the art high level API projects are mostly coupled with one framework, the model scripts are still developed ad hoc which makes efforts like TinyMS difficult to iterate.

## Proposal

In this repo, we propose a specification that standardize the model training scripts, respectively: 
* [model proto](../model.proto)
* [layer proto](../model.proto)
* [losses proto](../losses.proto)
* [vision proto](../vision.proto)
