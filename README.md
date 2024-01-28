# Assignment_Topsis_For_Pretrained_Models_Text_Summarization_102013040
## Title
Topsis For Pretrained Text Summarization Models 102013040
## Methodology 
<img width="682" alt="image" src="https://github.com/SanjanaSinha1/Assignment_Topsis_For_Pretrained_Models/assets/100065115/afd38662-1c74-483a-b0ca-ff4acbdb91b2">

## Description
1. Different models: BART, PEGASUS, T5, LEAD5, BERT are trained on the 
   same dataset.
2. They are evaluated on basis of ROUGE Values:<br>
   ROUGE-1 (Unigram Precision, Recall, F1):
   Gives more importance to matching unigrams (individual words) between 
   the generated summary and the reference summary.<br>
   ROUGE-2 (Bigram Precision, Recall, F1):
   Gives more importance to matching bigram between the generated summary 
   and the reference summary.<br>
   ROUGE-L (Longest Common Subsequence):
   ROUGE-L focuses on the longest common subsequence and is considered 
   useful for capturing longer phrases and word sequences. 
3. Apply Topsis and calculate topsis score.
4. Rank accordingly.

## Project Structure:
INPUT FILE (input_model_parameters.csv): The CSV file containing value of parameters for differnt models.<br>
OUTPUT FILE (result.csv): The csv file obtained after applying topsis containing topsis score and rank.<br>
GRAPHS (Models_vs_Topsis and Models_vs_Parameters): Charts visualising topsis score comparision and comparision of all parameter values for different models respectively.

## Result and Analysis:
Topsis Score and Rank obtained in result.csv
  <img width="606" alt="image" src="https://github.com/SanjanaSinha1/Assignment_Topsis_For_Pretrained_Models/assets/100065115/ce17b179-2516-4437-b646-0b76e662e3df">

Bar Graphs: Visual representation of performance metrics for each model and its topsis score.

![Models_vs_Parameters](https://github.com/SanjanaSinha1/Assignment_Topsis_For_Pretrained_Models/assets/100065115/7eb2f0e6-1385-4e3a-8cfa-bf8486b51517)

![Models_vs_Topsis](https://github.com/SanjanaSinha1/Assignment_Topsis_For_Pretrained_Models/assets/100065115/9711546f-b0e1-4fd2-a16b-98c21fd35e7f)

