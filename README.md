# BOB Hackathon

This repository is created for the BOB Hackathon. We have chosen Challenge 4 for this hackathon. Our idea is to automate the ground stage of a loan application, and its reach can be improved with time. We also intend to improve the feedback system by introducing Generative AI. Both of our approaches, along with the APIs required, are as follows:

## Loan Documentation and Processing

### IDEA:
Income proof documents and other financial documents can be uploaded to the bank's application, where a generative AI model will inspect them. The user will be informed about the amount of loan that can be sanctioned and any additional required documents. This process saves customers time and reduces manual effort. The model should also suggest the necessary requirements for an individual or group to avail of the loan.

### SOLUTION:
Concepts of Optical Character Recognition (OCR), Natural Language Processing (NLP), AI/ML models like Document Classification Model, and Information Extraction Model are used to assess the documents. Compliance is checked using a set of compliance rules, and the Trulioo API is used to verify the identity and compliance of the applicants.

### API’s required:
- Google Cloud Storage API or Azure Blob Storage API
- Microsoft Azure Computer Vision API
- Azure Cognitive Services - Text Analytics API
- Azure Machine Learning or Google AI Platform
- Microsoft Bot Framework
- Azure Functions
- Trulioo API or Azure Active Directory B2C
- DocuSign API or Adobe Sign API

## Feedback Collection and Resolution

### IDEA:
Feedback forms are provided to users to fill out. The generative AI model regularly checks these forms, classifies complaints under various departments, and sends emails addressing the issues faced by customers. Once a particular problem is fixed, other customers proceeding with the task that raised an issue are given a form asking if they have encountered the same issue.

### SOLUTION:
The idea can be turned into reality by using concepts of sentiment analysis, performing data analysis, and generating insights for process improvements. A feedback loop is established to encourage customers to provide their valuable feedback.

### API’s required:
- Microsoft Forms API
- Azure Cognitive Services - Text Analytics API or IBM Watson Natural Language Understanding API, Google Cloud Natural Language API
- Azure Communication Services or Twilio API
- Azure Synapse Analytics API or Microsoft Power BI API or Google Analytics API
- Azure Logic Apps
- SurveyMonkey API or Qualtrics API

