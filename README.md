# hexaware
**Automated Question Builder Application** - **(ASKIFY)**
Welcome to the Automated Question Builder Application! This project is designed to streamline the creation of question banks for training, assessments, and self-learning purposes using AI-powered technology. The application provides a user-friendly interface for generating Multiple Choice Questions (MCQs), coding questions, and other types of questions based on uploaded curriculum documents.

**Table of Contents:**
* Overview
* Features
* Technologies Used
* Usage
* Future Enhancements
  
**Overview:**

The Automated Question Builder Application is an AI-driven tool designed to automate the generation of question banks. It leverages natural language processing (NLP) and machine learning models to understand the content of the uploaded documents and generate relevant questions. The application is tailored for trainers, educators, and learners who want to create high-quality question sets efficiently.

**Features:**

*Role-Based Access: Supports different user roles, including Administrator, Trainer, and Employee, each with specific functionalities.

*Document Upload: Allows users to upload curriculum files in various formats (PDF, DOCX, TXT) to generate questions

*Question Generation: Automatically generates MCQs, coding questions, and custom questions using advanced AI models.

*LangChain Integration: Utilizes LangChain to generate questions and answers based on detailed document analysis.

*Notifications: Sends email notifications to users when a new question bank is generated.

*Downloadable Content: Users can download generated questions in PDF or Excel format.

**Technologies Used**

*Python: The core programming language used to develop the application.

*Streamlit: For building the web-based user interface.

*Transformers (Hugging Face): For NLP tasks and question generation.

*Sentence Transformers: For semantic similarity and matching.

*LangChain: For advanced document processing and question generation.

*FAISS: For efficient similarity search and retrieval.

*Spacy: For text processing and tokenization.

*PDFPlumber, docx: For extracting text from uploaded documents.

*smtplib: For sending email notifications.

*FPDF: For generating downloadable PDF documents.

**Usage:**

Once the application is running, users can interact with the web interface to:

*Select User Role: Choose between Administrator, Trainer, or Employee roles.

*Upload Curriculum: Trainers can upload curriculum files in PDF, DOCX, or TXT format.

*Generate Questions: Select the type of questions to generate (MCQ, Coding, or LangChain Generated) and specify the number of questions.

*Download and Distribute: Download the generated questions in PDF or Excel format for distribution.

*Receive Notifications: Trainers receive email notifications when new question banks are generated.


**Future Enhancements:**

We plan to implement the following features in future releases:

*Case Study Question Generation: Extend the application to support the generation of case study-based questions.

*Advanced Analytics: Provide insights and analytics on generated questions and assessments.

*Integration with Learning Management Systems (LMS): Seamlessly integrate with popular LMS platforms for automatic question bank uploads.

*Enhanced User Interface: Improve the UI for a more intuitive user experience.
