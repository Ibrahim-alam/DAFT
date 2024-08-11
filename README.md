# DAFT

## DAFT- Option 1: You can use one of the datasets to fine-tune any of the (base) models to perform a downstream task. This is option 1 of DAFT, and we are calling it FT (Fine-tuning base model on target domain).

## DAFT- Option 2: This is an option through which a DAFT model can be used. If we have a domain adjacent model (DAFT) that has been fine-tuned previously on similar task as the target task, then with some newly acquired data from the target domain we can fine-tune the DAFT models, i.e., DA(FT)^2.

## DAFT- Option 3,4,5: DAFT_Option_3,4,5: You can run this to get output for the option 3, 4 and 5 of DAFT, namely, DAFT^z, DAFT-E^z and DAFT-E. DAFT-E^z is the zero shot Ensemble of the output of all DAFT models. DAFT-E uses a few shot examples from the target domain to pick better performing DAFT models from a large pool of DAFT models.


## BERT_performance_pretuned_for_LEEP: Run this to get LEEP score
