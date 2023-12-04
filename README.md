# Deep-Conditional-Text-to-Image-Generation

## Introduction
Generation of images from the give text description is a multimodal problem,
where there are two tasks involved.
- The first one is to ensure that all the characteristics of the object that we want
to generate and the attributes of the object we want are properly encoded into
some form of textual representation.
- The second task is learn a mapping function which uses this encoded vector
with information about object to generate an image. Advances in deep
learning techniques has provided ways to tackle this problem as we possess
models which provide good feature representation and also are capable of
generating images from noise. Still, this problem far from completely solved

## Problem Statement
Given a single-sentence human-written description $\mathcal{S} = (\mathrm{w}_1, \mathrm{w}_2, \cdots, \mathrm{w}_n)$
learn a text feature representation that captures all the visual features present in
the sentence and use these features to synthesize a compelling image that a
human might mistake for real.

Datasets
We have used the 102 Category Flower dataset for the task.
Stats:
- Images per category of flower : [images per category](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/categories.html)
- No of images per category : 40 to 258
- No of description per image : 10
