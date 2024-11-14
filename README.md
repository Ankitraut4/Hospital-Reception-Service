# Hospital Reception Service

This project is a Hospital Reception Service / Hospital Management Portal designed to streamline communication between doctors and patients. Built using AngularJS for the frontend and Spring Boot for the backend, the system allows doctors to manage their appointments and patients to view their assigned doctors, appointments, and prescriptions.

Features

1 --> For Doctors:

1] Create Doctor: Register doctors with details like name, specialization, age, and gender.

2] View Patients: Doctors can see the list of their assigned patients and their details.

2 --> For Patients:

1] Create Patient: Register patients with details such as name, appointed doctor, date of admission, age, gender, and previous prescriptions.

2] View Doctor: Patients can view the doctor assigned to them along with their prescription history.


General Features:

Home Screen: A welcome page providing an overview of the application.

Show Doctor/Patient Information: Retrieve and display details of all registered doctors and patients.


Technologies Used

AngularJS:

    src folder:

         App Folder:
             
             create-doctor: For registering doctors with required fields (name, specialization, 
                            age, gender).

             create-patient: For registering patients with details (name, assigned doctor, date 
                             of admission, age, gender, prescription).

             home: Displays a welcome screen.

             show-doctor: Retrieves and displays doctor details.
             
             show-patient: Retrieves and displays patient details.

         Assets Folder: Contains application assets.
        
         Environment Folder: Manages environment configurations.



Backend

      Spring Boot:
           
           Controllers:
                 
                 DoctorController: Handles API requests for doctor-related operations.
                 
                 PatientController: Handles API requests for patient-related operations.

                 
          Entities:
                
                Doctor: Represents the doctor entity.
                
                Patient: Represents the patient entity.

          Repositories:
          
              DoctorRepository: Provides database access for doctor entities.
              
              PatientRepository: Provides database access for patient entities.
        
        Services:
             
             HospitalService: Contains business logic for the application.    

        Exceptions:

            DoctorNotFoundException: Handles cases where a doctor is not found.

            PatientNotFoundException: Handles cases where a patient is not found.     

        Application Entry Point:

            RestApplication: Main application file located in the webservices folder.   

Server:

     Embedded Tomcat Server:

       Since Spring Boot is being used, it typically comes with an embedded Apache Tomcat server for running applications.


            
How to Run the Application

1. Backend:

Install Java (JDK 11+).

Clone the repository and navigate to the backend project directory.


Run the Spring Boot application using:

mvn spring-boot:run

2. Frontend:

   Install Node.js and Angular CLI.

    Navigate to the frontend project directory.

   Install dependencies using:

   npm install

   Start the Angular development server using:

   ng serve

   Access the application in your browser at

   http://localhost:4200.

3. For DataBase

   I used H2-console

   
Screenshots:-

1. Home Screen

![Screenshot (8)](https://github.com/user-attachments/assets/267de766-87f9-47d4-81f4-7b916876b5c5)



3. Doctor Creation Page

   
![Screenshot (9)](https://github.com/user-attachments/assets/0ea1764e-c782-40e5-9a4f-05de95b6888a)

3. Patient Creation Page 

![Screenshot (11)](https://github.com/user-attachments/assets/9a9f593f-c39a-482e-b818-097267877003)

4. Search for Doctor (show-doctor)

![Screenshot (18)](https://github.com/user-attachments/assets/1638bcc8-e63b-4b6a-bb6d-b98a6da98a9b)

5. Search for Patient (show-patient)

![Screenshot (12)](https://github.com/user-attachments/assets/af0270fa-df19-407f-8975-c909fc2c59f9)


![Ankit's HOSPITAL and 5 more pages - Personal - Microsoft​ Edge 23-05-2022 14_32_39](https://github.com/user-attachments/assets/4976106a-608a-4f45-ac45-9ea49e525245)


6. Patients and their perceptions

![Ankit's HOSPITAL and 5 more pages - Personal - Microsoft​ Edge 23-05-2022 14_32_20](https://github.com/user-attachments/assets/6011ebc0-f832-4113-88c0-8c528faa103b)


![Ankit's HOSPITAL and 5 more pages - Personal - Microsoft​ Edge 23-05-2022 14_32_29](https://github.com/user-attachments/assets/bfe8f56a-96fa-44ac-bb79-62a38e28a1f8)


   
7. DataBase (H2-Console)

![H2 Console and 5 more pages - Personal - Microsoft​ Edge 23-05-2022 12_42_52](https://github.com/user-attachments/assets/5b099570-01a3-44fc-b2a6-e6a758db23d3)



![H2 Console and 5 more pages - Personal - Microsoft​ Edge 23-05-2022 12_42_41](https://github.com/user-attachments/assets/7d801478-0125-4ba6-8924-aa815a8d1737)

8. Junit testing:

![junit_testing](https://github.com/user-attachments/assets/699a344d-ce67-43ff-b583-2520144ff661)


![junittesting_1](https://github.com/user-attachments/assets/962864e4-20e5-44fa-8771-f9c8cbe6a78e)


![Screenshot (24)](https://github.com/user-attachments/assets/baf8af2d-0055-402f-a531-d1491354e981)









   



   
 



             
