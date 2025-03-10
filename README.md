# LLM-Phishing-Email Project
For this project, I used the final phishing email dataset and applied a large language model (LLM) for classification, utilizing Hugging Face and BERT. The goal was to train the model to classify phishing and legitimate emails.

Additionally, I performed preprocessing on the CEAS_08 dataset in the same way it was done to merge it with the phishing_email dataset, ensuring consistency. This part of the work, serves not only as a study for learning and understanding the methodology but also demonstrates how to replicate the process for practical applications.

<img align="center" alt="Coding" width="500" src="https://marvel-b1-cdn.bc0a.com/f00000000032040/cdn.prod.website-files.com/672e4d78ddc6417dc8ab2e1f/675a28b32b088f04d89ce051_32040_94c482e61bc04c5bb6a918a7cde3d962_1542746731.png">

### PHISHING EMAIL DATASET
This dataset was compiled by researchers to study phishing email tactics. It combines emails from a variety of sources to create a comprehensive resource for analysis.

Initial Datasets:
Enron and Ling Datasets: These datasets focus on the core content of phishing emails, containing subject lines, email body text, and labels indicating whether the email is spam (phishing) or legitimate.

CEAS, Nazario, Nigerian Fraud, and SpamAssassin Datasets: These datasets provide broader context for the emails, including sender information, recipient information, date, and labels for spam/legitimate classification.

Final Dataset:
The final dataset combines the information from the initial datasets into a single resource for analysis. This dataset contains:

Approximately 82,500 emails
42,891 spam emails
39,595 legitimate emails
This dataset allows researchers to study the content of phishing emails and the context in which they are sent to improve detection methods.

### Folders and Files:

visualizations: Imagens de gráficos gerados durante o desenvolvimento do projeto.

data_wrangling_ceas.ipynb: : A file replicating the data preprocessing applied to merge with the final project dataset. It also contains a brief data analysis of the final dataset.

llm_phishing_email.ipynb:  Contains the file for creating the BERT LLM algorithm. In this project, a data classifier was developed with over 99% accuracy.

### Autor:
Julio Martins

### E-mail: 
yamashitajulio@gmail.com

