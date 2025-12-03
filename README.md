  # Multi-language Online Bookstore Management System

## Project Overview

This project is a full-stack online bookstore management system designed to demonstrate proficiency in multiple programming languages and technologies. It integrates Java, SQL, Python, and C++ to deliver a comprehensive solution for managing books, orders, and analytics, along with a user-friendly website interface.
 
### Key Features 
  
- **Book Management:** Add, update, delete, and view books with details such as title, author, price, and stock. 
- **User  Orders:** Users can browse books and place orders (to be implemented).                      
- **Sales Analytics:** Python scripts analyze sales data and generate visual reports.                     
- **Recommendation Engine:** A C++ module provides personalized book recommendations based on purchase history.
- **Responsive Frontend:** A website built with HTML, CSS, and JavaScript interacts with backend APIs.   
      
---
 
## Technologies Used 
                
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)            
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)              
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)                          
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)                
                 
                                                                                                                                                                 
## <img width="725" height="342" alt="Screenshot 2025-10-02 022151" src="https://github.com/user-attachments/assets/5ee3662f-4e18-4e3b-817a-576823efa727" />                
## Project Structure                                                         
                                                                               
BookstoreProject/                                                          
├── backend/                # Java Spring Boot backend                                            
│   ├── src/        
│   │   ├── main/           
│   │   │   ├── java/com/example/bookstore/           
│   │   │   │   ├── controller/BookController.java          
│   │   │   │   ├── model/Book.java         
│   │   │   │   ├── repository/BookRepository.java        
│   │   │   │   └── service/BookService.java         
│   │   │   └── resources/application.properties         
│   └── pom.xml        
├── frontend/               # Frontend HTML, CSS, JS files           
│   └── index.html    
├── analytics/              # Python analytics scripts        
│   └── sales_report.py       
├── recommendation/         # C++ recommendation engine        
│   └── recommend.cpp       
└── README.md               # Project documentation       

# Setup and Installation
## Prerequisites                 
Java 17+ and Maven                            
MySQL or PostgreSQL database server                                
Python 3.x with mysql-connector-python and matplotlib                          
C++ compiler (g++, clang, or equivalent)                                  
Git (for version control)      

## Backend Setup (Java Spring Boot)
1. Navigate to the backend/ directory.             
2. Configure your database connection in src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/bookstore_db?useSSL=false&serverTimezone=UTC                      
spring.datasource.username=your_db_username                                    
spring.datasource.password=your_db_password                                                                                                 
spring.jpa.hibernate.ddl-auto=update                                                                      
spring.jpa.show-sql=true                                                                                                            
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect             
                                                          
3. Create the database bookstore_db in your SQL server.                                                            
4. Build and run the backend:                 
     
./mvnw spring-boot:run              

5. The backend API will be available at http://localhost:8080/api/books.                                   

## Frontend Setup        
1. Open the frontend/index.html file in your web browser.
2. The frontend interacts with the backend API to display books and place orders.                    

## Python Analytics
1. Navigate to the analytics/ folder.
2. Install required Python packages:

pip install mysql-connector-python matplotlib               

3. Run the analytics script:

   python sales_report.py
 
## C++ Recommendation Engine 
1. Navigate to the recommendation/ folder.                                  
2. Compile the C++ program:                               

     g++ recommend.cpp -o recommend

3. Run the executable:    

   ./recommend

## API Endpoints (Backend)   
<img width="681" height="352" alt="Screenshot 2025-10-02 025137" src="https://github.com/user-attachments/assets/045616d4-367c-4fb4-8189-d0a711602716" />

## Future Enhancements
1. User authentication and authorization                                              
2. Order management and payment integration                                              
3. Enhanced frontend with React or Angular                                              
4. Real-time analytics dashboard                                                 
5. Improved recommendation algorithm with machine learning   

## License  
MIT License

Copyright (c) 2024 Ayan Tyagi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.   

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contact
Ayan Tyagi                                                                
Email: ayan.tyagi2211@gmail.com                              
GitHub: https://github.com/ayaantyagi                                             
LinkedIn: https://linkedin.com/in/ayantyagi                                                         

Feel free to reach out for questions, collaboration, or feedback!

