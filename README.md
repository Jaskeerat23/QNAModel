# QNAModel
First Deep Learning Project

This project will be build in different phases, where every phase will focus on improving the model's perfomance

# Phase-1:
In this phase the focus will be building the model, the architecture of the model is inspired by encoder-decoder attention 
based mechanism. The flow of the model will be:
    1. User will choose Subject and difficulty
    2. For sake of simplicity there will be a python list of strings from which
       a random prompt will be selected and <SUB> and <DIFF> will be replaced 
       by subject and difficulty respectively, 
            for eg. Provide HARD question on PHYSICS
    3. Then this will go to an encoder module that will try to extract meaningful
       info and encode it
    4. Then using attention mechanism and the encoded info, hidden states decoder
       will try to generate meaningful text at each step

Initially the goal is to learn how attention works and how we can make a language model, so to make the data simple
we will use simple questions of 2-3 subjects
