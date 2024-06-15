<div align="center">

  <h1>NutriLens: NutriScore App for Healthy Lifestyle</h1>

</div>

# :open_book: About The Project
<table>
<tr>
<th>Team ID</th>
<th>Theme</th>
</tr>
<tr>
<td>
C241-PS146
</td>
<td>
Health Innovation: Empowering Vulnerable Communities for Health and Well-being
</td>
</tr>
</table>
<p align="justify">
  Our team wants to create a NutriLens application that can decipher nutritional information from packaged food and 
  beverages. Our project aims to address the issue of unclear and inaccurate understanding of nutritional information on 
  packaged food and beverages in Indonesia. This problem statement illustrates the increasing public awareness of the 
  importance of a healthy lifestyle, matched by the increasing consumption of packaged food and beverages. Through 
  investigating this research question, we sought to gain a deeper understanding of the definition of Nutri-score, 
  the problems faced in understanding nutritional information, the public knowledge of nutritional information and Nutri-score,
  awareness of nutritional information and Nutri-score impact consumer decisions, the factors that influence their perceptions,
  the state of relevant regulations, and the stakeholders involved. We highlight the importance of understanding balanced nutrition, 
  which is the basis for the urgency of increasing public awareness of nutritional information and Nutri-score in Indonesia.
  By applying scanner technology and machine learning, NutriLens will provide information regarding the nutri-score of the products. 
  We see the NutriLens App as a potential solution but recognize its implementation challenges. 
  By focusing on true problem-solving and adopting a design thinking approach, we hope to provide an effective solution for Indonesians to 
  make healthier food choices. 
</p>
  

# :wave: Us
  | ID         | NAME          | University                  | CONTACT                                                                                                                                                                                                                                                                                                                                                                                                                         |
  |------------|---------------|--------------------|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
  | M319D4KY2842  | Edbert |Universitas Sumatera Utara  | <a href="https://www.linkedin.com/in/edbert-b3a331269/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/Edbertt"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>                                                                                                      |
  | M278D4KY2622  | Rafael Simson Riston | Universitas Negeri Makassar | <a href="https://www.linkedin.com/in/rafaelsimsonriston/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/xochaels"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>
<!--  linkedin belum  cristo -->

# Repository  
| Path               | Link Repository                                                                                                                                                            | 
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Cloud Computing    | [Backend Services](https://github.com/NutriLens-Bangkit-2024/backend-services)                                                                                             |
| Machine Learning   | 1. [OCR](https://github.com/NutriLens-Bangkit-2024/nutrion_grade_scanning) <br/> 2. [Grade Clasification](https://github.com/NutriLens-Bangkit-2024/nutrition_grade_model) |
| Mobile Development | [App](https://github.com/NutriLens-Bangkit-2024/NutriLens_App)                                                                                                                                                                    |
## :cloud: Cloud Computing

  This application uses the HAPI framework in the process of creating APIs for data processing. the storage media used are cloud storage and firestore. then in the deploy process it uses a cloud run because it feels suitable for this application (cost effective and scalable). 
  
  *Teach Stack*:
  1. Hapi FrameWork: Framework that we use to create APIs in processing data needed in the application, such as registers, logins, data statistics and others.
  2. Cloud Storage: image data storage media in this application.
  3. FireStore: NOSQL-based storage of all data other than image data.
  4. Cloud run: a Google Cloud service that lets you run containerized applications without managing servers. It automatically scales with traffic and supports any language or framework in a container.

## :robot: Machine Learning
<p align="justify">
  The NutriLens application leverages two machine learning models to predict nutrition grades from food packaging. 
  The first model uses the PaddleOCR library to detect tables and extract text, while the second model employs
  a neural network for multi-class classification.
</p>
  

  *Teach Stack*:
1. PaddleOCR: Utilized to extract text from images of food packaging. Regex is used to filter and refine the extracted information.
2. Neural Network: A neural network is employed to classify the nutrition grade into 5 categories.
3. FastAPI: FastAPI is used to create a robust and scalable API for handling requests and serving the machine learning models.
4. Docker: Docker is used to containerize the application, ensuring a consistent environment for deployment and easy scalability.

## :iphone: Mobile Development
  Description ..
  
  *Teach Stack*:
  1. .
