# shufflers
An attempt to make machine learning models easily reproducable by taking out probabilities, by just using discrete maths to generate processes apriori. Mostly: Pre-settling quantity values given the distributions; pre-randomizing decisions, storing them with a "shuffleID".

Ideally, the project will make it possibly to run any complicated exploration-exploitation "distribution" for reinforcement learning models, by pre-determining decision values based on the given distribution - similarly to neural networks (SGD, dropout etc.)<br>
In many models, the randomized process isn't described with a distribution, but something more algorithmic - e.g. a Markov decision process - the library will also provide tools for this.
