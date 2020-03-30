# Clipper-test
Repository for testing dynamic inference with Clipper [Clipper](http://clipper.ai/)

## Dynamic Inference (Serving Models in Production via REST)
Inference is the term used to describe the process of using a pre-trained model to make predictions for unseen data.
Dynamic Inference is the term used to describe making predictions on demand, using a server. 

This notebook is a walk through for how to serve a machine learning model using a low latency prediction servering system called **[clipper.ai](http://clipper.ai/)**. 
clipper can be hosted on your favorite cloud provider or on-premise.

Overview 
+ Model training
+ Clipper cluster creation
+ App creation & model deployment
+ Model query (single row, multiple rows) via Python requests & curl
+ Model versioning update 
+ Model versioning rollback
+ Model replication

References:
+ [clipper.ai documentation](http://clipper.ai/)

+ [clipper @github](https://github.com/ucbrise/clipper)
