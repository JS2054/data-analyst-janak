# data-analyst-janak
Project Portfolio

Janak Prasad Subedi (2313234)

Project Analysis

Project 1: Descriptive Analysis – Analyzing Parks in the City of Vancouver

Project Description:


The project focuses on examining and extracting meaningful information from City of Vancouver park data. The analysis prioritizes evaluating park distribution by area while assessing park facilities alongside visitor tendencies. The descriptive analysis will deliver important findings to city planners, environmental analysts, and policymakers, who can use these insights to maximize resource utilization and upgrade facilities and overall park visitor experiences.
Project Title: Analyzing Parks in the City of Vancouver

Objective:


•	Analyze the geographical distribution of parks throughout the different regions of Vancouver.
•	Examine the facilities present in parks together with their usage patterns.
•	To develop recommendations for urban planners based on research-based analysis of data to improve urban green spaces.

Dataset:


The dataset includes information about 216 parks which provide names, facilities, advisories, washrooms, neighborhoods, and size measured in hectares. The research draws data from three different sources which include public city datasets, management reports, and direct surveys. The data consists of locations, amenities, and advisories in addition to the classification of nearby areas.

Key Findings from the Dataset:


Parks exist with different sizes between 0.09 hectares and more than 4 hectares.
Different parks feature various types of amenities including basic facilities and facilities with special features.
The location of neighborhoods affects how accessible and frequently parks are being used.
The geographic attributes of destinations within Google Maps enable users to examine the positions of various parks on maps.

Methodology:


Data Ingestion: Acquiring raw data from sources like APIs or cloud storage.

File pathway after data ingestion through Remote Desktop Connection (RDP)
![image](https://github.com/user-attachments/assets/7fbd1563-8d92-416c-ab39-ff2316502108)


Data Profiling: Examining data consistency and quality.

![image](https://github.com/user-attachments/assets/08a56c12-af91-4dd9-bb32-06b3c47e5940)


Data Cleaning: The process of data cleaning involves both error fixations and the removal of inconsequential data.

![image](https://github.com/user-attachments/assets/988d5b6a-fbaf-4323-bfad-8056e871be3c)


Data Cataloging: Organizing data for accessibility and usability.

![image](https://github.com/user-attachments/assets/62ee2531-f295-4025-a9a9-616142b23a73)


Data Summarization: The process of data processing yields insights by summarizing data through its analysis phase.

![image](https://github.com/user-attachments/assets/60bd15c9-9edb-49c8-bf57-5ea2ee3492fc)


Data Analysis: Data Analysis serves to extract beneficial information from the available dataset.

![image](https://github.com/user-attachments/assets/4fcb4d63-1159-4e71-a552-e9a5042d4d8b)


Business Questions:

![image](https://github.com/user-attachments/assets/20e6db3d-1fd4-40a8-a922-5967575690d9)

![image](https://github.com/user-attachments/assets/2dc6da09-fe8b-477c-853d-a71191cb1b9a)

![image](https://github.com/user-attachments/assets/65ce0bed-0ffb-438e-851a-678cf47d9599)


The analysis of the Parks in the City of Vancouver dataset evaluates three business-centric questions about park feature statistics including park size averages and special feature distributions and washroom amenity size differences between facility-equipped and facility-less parks. The survey presents opportunities to study park features and facilities so local governments can carry out better planning and resource management.

Data Security: Data security measures need implementation to stop unauthorized access to information.

Bucket Versioning & Encryption
![image](https://github.com/user-attachments/assets/2fa07e32-3cdb-4d8d-b8e0-527893f7b75a)


Data Governance: Management policies established by Data Governance standards provide both data compliance protection and proper data management.

![image](https://github.com/user-attachments/assets/12668a1e-d204-489c-91a9-b502eb84b76d)


Data Monitoring: Observing data activity and system performance.

![image](https://github.com/user-attachments/assets/d63e5102-d209-4c8e-9685-f7bb2be8080f)


Descriptive Statistics: The analysis calculates three fundamental metrics consisting of average park dimensions together with location data and visitor traffic records.


Data Visualizations: Visual data presentation involves deploying charts, and graphs to make data interpretations.


Summarized Graphs of Dataset

![image](https://github.com/user-attachments/assets/b479f088-b164-4695-825c-b18067f21d2e)

![image](https://github.com/user-attachments/assets/8d635d8b-0eee-4f4d-ae48-2bfcacc9c939)

![image](https://github.com/user-attachments/assets/e7bd4b50-c16d-4af2-82c6-258743111122)


Finding & Recommendations: The research gathered essential information that enhances the management of park resources.


To summarise this, the initial step in data work involves moving sources of data to an operational position where they become usable. Data quality assessment occurs through profiling activities after which cleaning steps eliminate errors and manage the absence of data values. The organizational practice of data cataloging makes data readily accessible to users. The process of data summarization reveals essential information together with significant patterns. Data analysis supports decision-making. Data security functions to prevent unauthorized persons from accessing data information. Data governance creates and implements data management procedures. The monitoring system tracks system utilization, and performance levels and ensures security along with operational efficiency.


Tools & Technologies:


This project heavily uses AWS cloud services and other tools and technologies.


•	AWS (S3, Glue, Data Brew, Beanstalk, CloudWatch, CloudTrail, KMS, Athena)

S3 Storing Data

![image](https://github.com/user-attachments/assets/9cb4a474-17c2-4811-a82e-47fc4bbe234f)

![image](https://github.com/user-attachments/assets/b90a6793-dca8-468f-96d1-9fb1a5fecccd)


Web Application through Beanstalk

![image](https://github.com/user-attachments/assets/919f4994-0d5b-499e-970d-f92e91e1bc86)


Key Management Service (KMS)

![image](https://github.com/user-attachments/assets/36d34c8e-36f1-40e3-a8c8-7e1bffb33e30)


Cloud Trial

![image](https://github.com/user-attachments/assets/70f75b93-a30e-44bd-8ec9-ef22422ecaaa)


S3 operates as a flexible container service that supports data storage and retrieval functions. Glue serves as a serverless service which makes data preparation easier for machine learning and analytics deployments. Glue Data Brew presents a graphical user interface that enables users to create normalized and clean data. Version 3.0 of Beanstalk enables users to deploy and manage web applications with a built-in automatic scalability feature. CloudWatch grants users important insights about their AWS resources and applications through observability functionalities. CloudTrail tracks events that document API activities along with AWS user actions performed in the system. Key Management Service makes it easy to handle cryptographic key composition as well as administration functions. Users can access S3-based data through SQL language applications by using Athena as an interactive service.

 
•	Drwa.io


The diagram software Draw.io enables users to build data analytic platform diagrams.  


![Janak Portfolio -CC Solution #5 drawio](https://github.com/user-attachments/assets/3495cb5a-1223-44d8-9245-ce704e8e1704)


 
The visualized data analytic platform (DAP) serves as a data processing system built to handle Vancouver parks information. The image displays the data path through several essential processing steps which start with ingestion before moving to summarization. Data ingestion processes occur on the left section of the diagram it shows how raw information arrives from multiple sources. Data cleaning together with transformation appear in the central section because they form the basics for achieving data quality. Data cataloging services are shown on the right side while structured table systems maintain data accessibility through proper labeling as the main features. The diagram presents a comprehensive structure of the DAP design which shows data movement from intake to summary processing to support insights extraction from the Parks in the City of Vancouver dataset.


•	Powershell


Through PowerShell, users can execute commands from a command-line interface to automate procedures for uploading Amazon S3 data.    

![image](https://github.com/user-attachments/assets/8046b455-f9c5-4f1f-b220-159885956ff1)


Deliverables:

The deliverables from both projects are mentioned below:

•	A data analytic platform (DAP) design.    
•	The data analysis of Parks in the City of Vancouver.    
•	Uploaded data in S3.    
•	Data profiling summary.    
•	The Parks in the City of Vancouver dataset underwent cleaning procedures.    
•	Data catalog for the parks in the city of Vancouver dataset.    
•	Summarized park-related data.    
•	All summarized data appears in the user interface stored within the S3 bucket.    
•	Database tables.    
•	The web application development proceeded through Beanstalk.    
•	Summarized graph of the dataset.    
•	High-quality Data Quality Analysis Table.    
•	The output from running the job.    


Conclusion


The Analyzing Parks in the City of Vancouver project establishes a systematic method to analyze and handle Vancouver park data for better park facility distribution observations and visitor trends assessment. As part of its functions, continuous improvements occur in green space administration along with increases in park community participation. Additional developments can include real-time visitor insights and predictive analytics for more intelligent urban planning.








