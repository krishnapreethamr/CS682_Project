This is the code of the project on Evaluation of Vision-Language Models

Install the required files from requirements.txt

**Datasets:**
*Object Recognition*

*Visual Question Answering (VQA)*
https://www.vision.caltech.edu/datasets/cub_200_2011/
Download the dataset and place it in VQA/data folder, update the path of the data in the code if needed.


**Running:**
*Object Recognition*
To map xml to coco annotation run the Notebook file xml_to_coco.ipynb in Object_Recognition/code folder
To run the DETIC model on the PASCAL_VOC dataset run the Notebook file detic-evaluation.ipynb in Object_Recognition/code folder

*VQA*
To run the BLIP model script, execute the following command:
```bash
python blip_model.py
```
Note: Change the path of the datasets accordingly

**File Structure**
```bash
CS682_Project/
├── Object_Recognition/
    ├── code/
        ├── detic-evaluation.ipynb
        ├── xml_to_coco.ipynb
    ├── data
        ├── annotated_custom_dataset
        ├── Custom dataset
        ├── pascalVOC                
├── VQA
    ├── code/
        ├── blip_model_color.py
        ├── blip_model_shape.py
        ├── evals.py
    ├── blip_model.py
    ├── caltech_birds_albef.ipynb
    ├── caltech_birds_blip.ipynb
    ├── zeroshot.ipynb     
├── README.md                       
└── requirements.txt
```


This Project has been done as a part of CS 682 Computer Vision at George Mason University under the guidance of Prof. Jana Kosecka<br />
Contributors for this project: <br />
1. Sumanth Manduru <br /> 
2. Swathi Guptha <br />
3. Krishna Preetham Rachakonda <br /> 


