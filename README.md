# Hospitaldatabase
This is the second  attempt of Database assignment, the first of which is also on public view names Assessment1
Hospitaldatase repo includes documents for reference, list of codes used and thought process for the layout of the project. 
Database itself is labelled resionalhospitaldata.sql and including different hospitals, doctors assigned, patients and prescriptions
Creating a hospital database with Entities being hospitals, doctors, patients and prescriptions.
Each table is related to the other by their primary and foreign key as per erd diagram included in repo

Relationships patients to doctors relationship is one to one 
hospitals to doctors 1 to many 
doctors to patients many to many 
patients to prescriptions 1 to many 
doctors to prescriptions many to many

Queries tested : Print a list of all doctors with hospital ID 3 
Print a list of all prescriptions for patient_id 621
 Print a list of all prescriptions doctor_id 20 has written 
Added new patient using auto_increment assigned to doctor_id 20 rachael dave 1990-01-01 1 Darent Club, WA 10465, Patient , 20

To use repo:
Git clone https://github.com/Devi1042/Hospitaldatabase.git

See codes for sample codes to select, add and join tables
Regionalhospitaldata1.sql shows the doctors, patients and prescriptions tables
See Plan for assignment to uderstand my thinking
