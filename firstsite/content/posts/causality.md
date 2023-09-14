---
title: "Causality"
date: 2021-04-09T11:48:18+01:00
draft: true
---

What is causal inference? Do we really need it? Is it useful in its current formulation?
<!--more-->

## Causal inference

I shall do my best to explain causal inference. We are not going to try to unpick whether causality really exists, with a philosophical approach, we are merely going to define causality as it is commonly thought of by people - it is the act of an event leading to another event occurring. We ought to define a couple of brief conditions - firstly the cause must precede the effect temporally. Secondly, if, in an other wise identical and parallel universe the first event did not occur, then the second event would not have occurred. This condition for causality is of course impossible to test - however it gives a good intuition for what we mean by causality.

Now we need to answer why we are interested in causality.

The key thing to think about is that many current machine learning processes work brilliantly without a second thought regarding causality. During training, they look at inputs (e.g. number of bedrooms, size of the garden, distance to London), find a way to map them to known outputs (e.g. house price), and then use the model to make predictions when we don't know what the output (answer) should be, but we do have the inputs. ML algorithms are incredibly good at this, and they are pervasive in day-to-day life.

But in many cases we can't understand what the machine learning algorithms are doing to the inputs to predict the output. In these cases, we only learn a very limited amount about the mapping between the inputs and outputs. By that, I mean that we do not understand what is **causing** the algorithm to predict what it does. And hence we do not glean anything about the mechanisms that drive the relationships between inputs and outputs.

So how do we get to this?
