# MorphVLM: Towards more Efficient and Robust Multimodal Vision Language Models
### CSCI-544 NLP Project - Fall 2023

## Abstract
In the rapidly evolving realm of multimodal language models, the need for efficient fine-tuning methodologies becomes increasingly vital. This work concentrates on refining the utilization of pre-trained multimodal vision language models, specifically optimizing their performance under hardware resource constraints. Acknowledging that harnessing powerful models often requires substantial computational resources and extensive datasets, our objective is to democratize the fine-tuning process, ensuring accessibility and impact across diverse applications. Through targeted experiments in Visual Question Answering (VQAv2) and medical domain tasks using A-OKVQA and PubMedQA datasets, we navigate the delicate balance between performance and resource efficiency. Leveraging the OpenFlamingo framework, our work explores the potential of large pre-trained Visual Language Models (VLMs) through component substitution and domain adaptation experiments.


## Code details
```pip install -r requirements.txt```
and then run jupyter notebooks:

* `eval_script(VQAv2).ipynb` evaluates the model on VQAv2 Val dataset. Using open-flamingo framework with various 
* `PubMedQA_dataset_script.ipynb` is used for fine-tuning the model on PubMedQA dataset
* `run_open-flamingo.ipynb` creates an interface to query the open-flamingo model and generate results

## Sample Output
![Model Output](https://github.com/punith300i/nlp-vlm-project/blob/main/model_output_sample.png?raw=true)

## Equal Contributors:

* Chirag Khatri
* Mihir Mangesh Pavuskar
* Prince Verma
* Pothula Punith Krishna
* Lavrenti Mikaelyan

