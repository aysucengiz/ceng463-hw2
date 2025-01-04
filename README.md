# CENG463 - HW2

# Task

Both tasks are identical, with task 1 using orientation dataset and ask 2 using power dataset. Main distinction between them is for masked lm, task 1 does fine-tuning and evaluatoin on original language whereas task 2 does on English translation of the original text.

## Prepare the Data
Downloads the dataset, chooses the predetermined language and splits the training data. Must be run everytime for the code to be functional.

## Masked LM
Uses XLMRoberta, can be run independently of the "Causal LM" section. For the Turkish dataset (biggest), fine-tuning takes approximately an hour with T4.

## Causal LM
Uses distilgpt2, can be run independently of the "Masked LM" section. Does a total of 4 evaluations, details can be found in ipnyb files. Fine-tuning is done 2 times, takes up approximately 20 minutes with T4.

## Results
Results of the evaluations.
