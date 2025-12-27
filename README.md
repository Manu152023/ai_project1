# Resume Screening and Scoring System (RESSC)

The Resume Screening and Scoring System is a machine learning based application designed to analyze resumes, extract relevant skills, evaluate resume quality, and compute job matching scores. The system helps automate the initial stage of recruitment by reducing manual effort and improving screening accuracy.

## Features

- Resume upload and analysis
- Automatic skill extraction
- Resume quality scoring
- Job and resume similarity matching
- Machine learning model integration
- Web based interface
- Backend implemented using Python and Flask

## Technologies Used

- Python
- Flask
- Machine Learning
- Natural Language Processing
- Scikit-learn
- HTML
- Pickle

## Project Structure
```
ressc/
│
├── app.py
├── index.html
├── requirements.txt
├── resume_model.pkl
├── procdata.csv
├── static/
├── uploads/
└── README.md
```
## Working of the System

1. The user uploads a resume
2. Resume text is extracted
3. Skills and keywords are identified
4. Resume quality score is calculated
5. Machine learning model evaluates similarity
6. Results are displayed on the web interface

## Machine Learning Details

- Model used for classification and similarity scoring
- Feature extraction using NLP techniques
- Trained model stored using Pickle format

## Future Enhancements

- Support for PDF resume parsing
- Multiple job role matching
- Skill gap analysis
- Improved user interface
- Database integration
