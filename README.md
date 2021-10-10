# Knowledge Graph Embedding
A TensorFlow-based implementation of knowledge graph embedding models.  
Document available here: https://knowledge-graph-embedding.readthedocs.io/en/latest/index.html

## Todos
[] finish docs
[] model saving
[] early stopping with ranking metric (for now using validation loss)
[] reproducible paper experiment

## Models
Including following knowledge graph embedding model:
### Translating Based
* Unstructured Model (UM)
* Structured Embedding (SE)
* TransE
* TransH
* TransR
* TransD
* RotatE
### Semantic Based
* RESCAL
* DistMult

## Loss
* Binary Cross Entropy Loss
* Pairwise Hinge Loss
* Self Adversarial Negative Sampling Loss
* Square Error Loss

## Score
* Dot
* Lp-Distance
* Squared Lp-Distance

## Constraint
* Lp-Regularization
* Clip Constraint
* Nomalized Embedding
* Soft Constraint

## Negative Sampling Strategy
* Uniform Strategy
* Typed Strategy
