#  Myers-Briggs Personality Type Prediction with Text Classification

Semester Project of course *Introduction to Machine Learning* (CompSci 289A) at UC Berkeley with Prof. Jonathan Shewchuk, Spring 2022

- [Final Report](https://github.com/6shun/mbti-classifier/blob/main/doc/Final_Project_Report.pdf)
- [Presentation Slides](https://github.com/6shun/mbti-classifier/blob/main/doc/Final_Presentation_Slides.pdf)

This repo is structured as following:

```
.
├── data                            
│    ├── cleaned_mbti_train.csv           # Cleaned train data
│    ├── class16_mbti_map.npy             # Cleaned test data
│    └── class16_mbti_map.npy           
├── docs                                 
│    ├── Final_Project_Report.pdf         # Final Project Report
│    └── Final_Presentation_Slides.pdf    # Project Presentation Slides
├── notebooks                             # Collection of notebooks
│    ├── bestmodels.ipynb                 # Best model of each classifier, final parameter
│    └── bestmodels_include_tuning.ipynb  # Best model of each classifier, tuning process
└── README.md
```