# SOF-Laytime-Calculator
 Hackathon Project – Extract structured events (arrival, berthing, loading, etc.) from Statements of Facts in PDF/DOCX format.  

Inspiration:  
In maritime operations, Statements of Facts (SoFs) record crucial events of a ship’s port stay.  
But they’re usually messy PDFs or Word docs, making it hard to analyze them quickly.  

We built SoF Event Extractor to automatically convert unstructured SoFs into clean, structured data.  



What It Does  :
 Upload a PDF or DOCX SoF document  
 Extracts event names, start time, and end time  
 Outputs results in a structured table  
 Export results as CSV or JSON  
 Also provides a REST API endpoint  


Tech Stack : 
Backend: Python + Flask  
Parsing: pdfplumber, python-docx,  
Frontend: HTML
Output: CSV, JSON  

 Project Structure:
SOF-LAYTIME CALCULATOR
│── app.py
│── extractor.py 
│── templates/ 
│ ├── index.html
│ └── result.html
│── uploads/ 
│── requirements.txt 
│── README.md 


Usage:
1. Upload a .pdf or .docx file .
2. Click Extract Events.
3. See structured events .
4. Download results as .csv or .json.
   
   Future Improvements :
1.  Better event extraction with NLP
2.  Support for Excel input files
3.  Add user authentications & history tracking
4.  Deploy on cloud (AWS/Heroku/Render ) 
