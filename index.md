---
layout: default
title: Rohan Raval
---

## About Me

- **Name:** Rohan Raval
- **UCSD Email:** [rraval@ucsd.edu](mailto:rraval@ucsd.edu)
- **Section:** D09
- **Mentors:** Professor Nicholas Boechler and Professor Igor Sfiligoi

## Methodology Assignment 4

**1. What is the most interesting topic covered in your domain this quarter?**

The topic I found most interesting this quarter was diffusion models, mainly because of how they are being used in our capstone project. We are trying to figure out what a metamaterial should look like if we want it to follow a particular stress-strain curve. I had mostly thought of diffusion models in the context of image generation before this, so seeing one being used to solve an inverse design problem was interesting. It gave me a better idea of how these models can be useful in engineering problems as well.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For Quarter 2, I would like to continue working with the same paper we have been trying to reproduce this quarter. This time, though, I want to see if we can make the authors' model smaller while keeping its accuracy the same or possibly improving it. We would start by reducing the number of channels and parameters in the model and seeing how that affects its performance. Depending on what we find, we could also experiment with changing parts of the architecture itself. The goal would be to find out how much we can simplify the model before its performance starts to suffer.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

One thing I would change about my approach this quarter is getting access to Cosmos earlier so I could run the model myself. I wasn't able to get access for various reasons, which meant I couldn't personally train or test the model on the cluster. I think being able to do that would have helped me understand the implementation better, especially the training process and how the model behaves when we change different settings. That is something I would want to do differently going into Quarter 2.

**4. What other techniques would you be interested in using in your project?**

I would be interested in exploring reinforcement learning as another approach to our problem. Right now, the diffusion model works by gradually denoising an image to generate a metamaterial design. With reinforcement learning, we could instead try having an agent make changes to a design based on how closely its stress-strain response matches the target curve. I have studied reinforcement learning before, so I would be interested in seeing how well it works on this kind of problem. It would also be interesting to compare the designs found by both methods and see whether reinforcement learning can come up with solutions that the diffusion model misses.
