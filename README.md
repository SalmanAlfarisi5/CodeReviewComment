# Dataset Description
In the software industry, when a developer develops a piece of code, it does not get merged with the main code base instantaneously. The code first goes through reviewers (senior developers typically) for proper quality control. These reviewers provide some feedbacks to the developer for improving certain aspects of the code. This dataset is about predicting what sort of operation (insertion / deletion / replacement) is desired from the devloper given the review comment as input. 

# Dataset Details
- Two files - (1) Train.xlsx and (2) Test.xlsx
- Each sample consists of a review message and the expected operation
- The dataset has a lot of different words, programming jargons and limited number of samples to work with
- The dataset has been extracted from: https://arxiv.org/pdf/2307.03996

# Expected Task Description
- You need to train and tune your model using Train.xlsx and test on Test.xlsx
- You should explore the use of pretrained language models for this task
- You should also try using pretrained word embeddings for word level representation of the review messages
- Since the number of samples is limited, you can also use classic ML techniques with well through feature extraction