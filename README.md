## BinaryVQA:
Binary VQA test set for testing Visual Question Answering Models

- Our dataset comprises 7,800 carefully formulated and manually verified binary questions, covering a diverse range of objects, topics,
and concepts, with 1,024 associated images

- The median question length is 5, and there are typically 7 questions per image.

- Approximately 63% of our questions have positive answers.

- Approximately 63% of our questions have positive answers. One of the leading VQA models, known as OFA, achieves an accuracy of 75% on BinaryVQA, which is significantly lower than its performance on the VQA v2 test-dev dataset (94.7%).

- We also introduce a new score called “ShuffleAcc" to compensate for the yes/no imbalance in answers by sampling questions. We find that tested models are not biased towards positive answers.


## Data:
We have made our code and data accessible to the public at https://drive.google.com/file/d/18g0AV6xdSGGMc4Bg0vQ2U6KR7K1_Jo6W/view?usp=sharing


## Tested models:
- OFA
- A simple baseline model: https://github.com/iamaaditya/VQA_Demo/blob/master/Visual_Question_Answering_Demo_in_python_notebook.ipynb
- Pythia


To explore the dataset, please explore the the jupyter notebook.




## Licence: 

BinaryVQA is licensed under the Creative Commons Attribution 4.0 license.



## Citation:

@article{borji2023binaryvqa,
  title={BinaryVQA: A Versatile Test Set to Evaluate the Out-of-Distribution Generalization of VQA Models},
  author={Borji, Ali},
  journal={arXiv preprint arXiv:2301.12032},
  year={2023}
}
