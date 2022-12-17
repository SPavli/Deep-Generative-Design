# Deep-Generative-Design

In an urban context that needs to be constantly adapted to global crises, population movements, climate change and economic crises, designers and engineers strive to configure solutions that respond to multiple criteria. Within this framework, the concept of generative design is gaining more and more ground in the construction field, allowing rapid design space exploration, optimization and decision making for complex design problems.

This thesis implements an experiment in a common design problem such as optimizing the topology of shell structures for structural performance, using an Artificial Intelligence Framework. To implement this experiment a novel dataset consisting of various mesh tessellations is created. The next step is to design a generative workflow that combines unsupervised and supervised learning along with a Gradient Descent Algorithm for pattern generation, structural performance estimation and optimization. A Variational Autoencoder is trained to generate new mesh tessellations and a Surrogate Model is used to predict the structural performance of the decoded designs. Finally, a Gradient Descent Algorithm searches the latent space of the Variational Autoencoder for optimum solutions.

![3](https://user-images.githubusercontent.com/120601318/208213574-ed2cec1c-6241-43da-92d7-844ee1b03205.jpg| width=100)


The results show that the proposed Artificial Intelligence workflow is able to generate novel and structurally better performing solutions that those existing in the training dataset. The findings of this thesis indicate that Artificial Intelligence can be successfully integrated into the concept of Generative Design to optimize shell structures.
 
![1](https://user-images.githubusercontent.com/120601318/208213648-fedf954a-1653-43e1-8a58-2999df897fd1.gif)


Full report here: http://resolver.tudelft.nl/uuid:01c2da7f-7718-495c-a304-ce142abc1426
