# Hospital Administration 

## Project overwiew
- Developed a project based on Java-Spring Boot, which was built using Maven. As part of the project, created REST APIs that can be used to access the application’s functionalities. This software serves as a hospital administration tool that allows the storage of patient and doctor information. By capturing patient concerns, the system can effectively allocate a suitable doctor for each case. Additionally, searching for a patient by their patient ID enables easy tracking of the assigned doctor..To ensure the APIs are functioning correctly, I have tested them using POSTMAN.

## Tech Stack
- Java
- Spring Boot
- MySQL

## Controller
- DoctorController
- DoctorController

## Repository (Dao)
- DoctorRepo
- PatientRepo

## Model
- DoctorModel
- PatientModel

## Service
- DoctorService
- PatientService

## DataBase Used
- SQL DataBase


## Feature
Using REST APIs, save information about patients and doctors. Then, based on their concerns, assigned a doctor to a patient, and used the doctor ID to enable the patient to consult with their respective doctor and connected to MySQL Database.

### Doctor 
 - PostMapping -> http://localhost:8080/Hospital/Doctor/addDoc
 - GetMapping  -> http://localhost:8080/Hospital/Doctor/GetDoctor/Details
 - GetMapping  -> http://localhost:8080/Hospital/Doctor/GetDoctor/Details/docId/3 (By Id)
 - PutMapping  -> http://localhost:8080/Hospital/Doctor/Update/Doctor/docId/2
 - DeleteMapping -> http://localhost:8080/Hospital/Doctor/Delete/Doctor/docId/5

### Patient
 - PostMapping -> http://localhost:8080/Patient/Add/patient/Details
 - GetMapping  -> http://localhost:8080/Patient/Get/Patient
 - GetMapping  -> http://localhost:8080/Patient/GetPatient/patId/2
 - PutMapping  -> http://localhost:8080/updatePatient/patId
 - DeleteMapping -> http://localhost:8080/DeletePatient
 
## Contributing
- If you would like to contribute to this project, please open a pull request.
