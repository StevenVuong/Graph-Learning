# Other Tutorial Resources

- [Graph Neural Networks on Social Networks](https://www.kaggle.com/code/awadelrahman/tutorial-graph-neural-networks-on-social-networks): Binary classification problem of whether Github users belong to a Machine Learning community or not.
- [Mnist Graph Deep Learning With Visualisations](https://www.kaggle.com/code/kmader/mnist-graph-deep-learning/notebook): Spektral MNIST example with visualisations of graph classification. Two interesting numpy functions; .unravel() and .swapaxes()
- [Neo4J MovieLens Recommendations](https://towardsdatascience.com/integrate-neo4j-with-pytorch-geometric-to-create-recommendations-21b0b7bc9aa): Pretty much what we want to do in linking companies to investors for Honeycomb; we want to somehow encode funding round information also. Maybe that can be a v2
- [Tabular To Graph](https://github.com/zjost/blog_code/tree/master/tab2graph_fraud?ck_subscriber_id=1374547752&utm_source=convertkit&utm_medium=email&utm_campaign=Tab2Graph+webinar+starting+in+1+hour%20-%208550613) Zak Jost walkthrough using DGL
  - IDs are typically good node candidates as they are unique
  - Attributes with a handful of unique are candidates for categorical features
  - We can typically scale via log transform any dollar amount
  - We want to identify fraudulent nodes, transaction idx
