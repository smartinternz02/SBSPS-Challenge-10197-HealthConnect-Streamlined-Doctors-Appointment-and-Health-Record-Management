# SBSPS-Challenge-10197-HealthConnect-Streamlined-Doctors-Appointment-and-Health-Record-Management
HealthConnect: Streamlined Doctors Appointment and Health Record Management

### Redhat with docker project link(live)
https://django-ibmdb-final-shaiksaiteja-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com/

# credlybadges :

### Saiteja Shaik
https://www.credly.com/badges/862426f8-ec3a-4e2d-a40b-977a768555f2/public_url
https://www.credly.com/badges/d62ce597-c7c3-4856-8701-b9c935d07e19/public_url

### Akshaya kumar S
https://www.credly.com/badges/affb0c6f-ee61-4a73-8714-54cd0ec73636/public_url
https://www.credly.com/badges/05462b1a-ae8f-43dd-a8d7-66f6bc8fb0eb/public_url

### Raju Konna
https://www.credly.com/badges/e41370d7-5bbb-4a1f-a21d-326567e65fc0/public_url
https://www.credly.com/badges/700c175b-bd39-4509-887f-6dd2e1981615/public_url

### Venkata Ramulu Y
https://www.credly.com/earner/earned/badge/1872ec2f-8190-40f1-a08d-fab1a13cc57a
https://www.credly.com/earner/earned/badge/9cd50e47-9691-4ee3-a0e5-3ecbdcda5e02


# Hospital Management
---
## screenshots
### Homepage
![homepage snap](https://github.com/smartinternz02/SBSPS-Challenge-10197-HealthConnect-Streamlined-Doctors-Appointment-and-Health-Record-Management/assets/109669265/88218e85-5bcc-46ed-8258-b2b299386154)

### Admin Dashboard
![admin dashboard](https://github.com/smartinternz02/SBSPS-Challenge-10197-HealthConnect-Streamlined-Doctors-Appointment-and-Health-Record-Management/assets/109669265/af3eb626-bb65-4a91-b017-0eb304baa04e)

### Invoice
![invoice snap](https://github.com/smartinternz02/SBSPS-Challenge-10197-HealthConnect-Streamlined-Doctors-Appointment-and-Health-Record-Management/assets/109669265/0bfc83e3-15af-4a1c-bb20-ef707dd5bd9f)

### Doctor list
![doctor snap](https://github.com/smartinternz02/SBSPS-Challenge-10197-HealthConnect-Streamlined-Doctors-Appointment-and-Health-Record-Management/assets/109669265/93e8cc6d-2868-4da8-abd3-65a8ea65a5fb)

---
## Functions
### Admin
### username:  admin
### password:  admin       (no spaces before and after admin)
- Signup their account. Then Login (No approval Required).
- Can register/view/approve/reject/delete doctor (approve those doctor who applied for job in their hospital).
- Can admit/view/approve/reject/discharge patient (discharge patient when treatment is done).
- Can Generate/Download Invoice pdf (Generate Invoice according to medicine cost, room charge, doctor charge and other charge).
- Can view/book/approve Appointment (approve those appointments which is requested by patient).

# DATABASE IBM DB2 CONNECTION PRESENT IN INSIDE  hospitalmanagement/hospital/models.py   AND   hospitalmanagement/hospital/views.py

### Doctor
### username:  doctor
### password:  doctor       (no spaces before and after doctor)
- Apply for job in hospital. Then Login (Approval required by hospital admin, Then only doctor can login).
- Can only view their patient details (symptoms, name, mobile ) assigned to that doctor by admin.
- Can view their discharged(by admin) patient list.
- Can view their Appointments, booked by admin.
- Can delete their Appointment, when doctor attended their appointment.

### Patient
### username:  patient
### password:  patient       (no spaces before and after patient)
- Create account for admit in hospital. Then Login (Approval required by hospital admin, Then only patient can login).
- Can view assigned doctor's details like ( specialization, mobile, address).
- Can view their booked appointment status (pending/confirmed by admin).
- Can book appointments.(approval required by admin)
- Can view/download Invoice pdf (Only when that patient is discharged by admin).

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install ibm_db
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc(local)
```
http://127.0.0.1:8000/
```


## Feedback
Any suggestion and feedback is welcome. You can message me on LinkedIn
- [Contact on LinkedIn]
- (https://www.linkedin.com/in/shaiksaiteja)
