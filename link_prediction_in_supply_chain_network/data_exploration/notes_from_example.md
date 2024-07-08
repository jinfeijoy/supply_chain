# Notes from code: link prediction supply chain 

1. load data: ``ingestion/dataloader.py``
2. load training data: ``ingestion/dataloader.py``
3. create graph model: ``utils.py/create_model``
4. train graph model on training data: ``managers.trainer``
5. get test data: ``ingestion/dataloader.py``
6. evaluate model on test data: ``managers.evaluator``