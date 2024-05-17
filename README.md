## โครงสร้างไฟล์ส่วน Front-end
```bash
TU-WELLNESS_CENTER
├── README.md
├── .vercel
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── api
    │   └── axios.js
    ├── assets
    ├── component
    │   ├── AuthStatus.js
    │   ├── ErrorPage.js
    │   ├── GoBack.js
    │   ├── Loading.js
    │   ├── LoginMenu.js
    │   ├── NotFound.js
    │   ├── RequireAuth.js
    │   └── UnauthorizeError.js
    │
    ├── layout
    │   ├── HistoryLayout.js
    │   ├── LayoutBarchart.js
    │   ├── LayoutBarchartPsy.js
    │   ├── MainLayout.js
    │   └──  SidebarLayout.js
    ├── page
    │   ├── Adminpage
    │   │   ├── Barchart
    │   │   │   ├── BarChartdiagosisPage.js
    │   │   │   ├── BarChartmedicalSup.js
    │   │   │   ├── BarChartnursingactivities.js
    │   │   │   └── BarChartorganizations.js
    │   │   ├── AddDianosisPage.js
    │   │   ├── AddMedicalSuppliesPage.js
    │   │   ├── AddmedicationPage.js
    │   │   ├── AddNursingActivitiesPage.js
    │   │   ├── DetailMedicalSuppliesPage.js
    │   │   ├── DetailsMedicalPage.js
    │   │   ├── DiagnosisPage.js
    │   │   ├── MedicalSuppliesPage.js
    │   │   ├── MedicationsPage.js
    │   │   ├── NursingActivitiesPage.js
    │   │   ├── PatientPage.js
    │   │   ├── RegisterPage.js
    │   │   ├── UpdateDiagnosisPage.js
    │   │   ├── UpdateMedicalPage.js
    │   │   ├── UpdateMedicalSuppliesPage.js
    │   │   ├── UpdateNursingActivitiesPage.js
    │   │   ├── UpdatePatientPage.js
    │   │   └── UserPage.js
    │   ├── Nursepage
    │   │   ├── Form
    │   │   │   ├── FormAddGeneral.js
    │   │   │   ├── FormChecklist.js
    │   │   │   └── FormMedicalRecord.js
    │   │   ├── AddpatientPage.js
    │   │   ├── EditmedicalrecordPage.js
    │   │   ├── HistorymedicalPage.js
    │   │   ├── ManagementPage.js
    │   │   ├── MedicalRecordByPatientPage.js
    │   │   ├── NewmedicalRecordPage.js
    │   │   ├── ProfilepatientPage.js
    │   │   ├── SearchPatientPage.js
    │   │   ├── UpdateProfilepatient.js
    │   │   └── ViewMedicalRecordPage.js
    │   ├── Psychologistpage
    │   │   ├── Barchart
    │   │   │   └──  Barchartpsy.js
    │   │   ├── AddpatientByPsy.js
    │   │   ├── AddpatientByPsy.js
    │   │   ├── AddpatientByPsy.js
    │   │   ├── Appointmentpage.js
    │   │   ├── CounselingByPatietnpage.js
    │   │   ├── DetailHistorypage.js
    │   │   ├── Generaldatapage.js
    │   │   ├── Newcounselingpage.js
    │   │   └── SearchPsy.js
    │   ├── FormPage
    │   ├── AddpatientByStd.js
    │   ├── HomePage.js
    │   └── LoginPage.js
    ├── utils
    ├── App.css
    ├── index.css
    └── index.js
```

## โครงสร้างไฟล์ส่วน Back-end

```bash
Data_Medical_Room
├── README.md
├── .env
├── node_modules
├── package.json
├── .gitignore
├── index.js
├── config
│   ├── dbConfig.js
│   ├── dbConnect.js
│   └── rolesList.js
├── controller
│    ├── PsychologistController
│    │   ├── Psy_AppoinmentDBController.js
│    │   ├── Psy_counselingRecordDBController.js
│    │   └── Psychologist_PatientDBController.js
│    │
│    ├── activitiesDBController.js
│    ├── authDBController.js
│    ├── cheklistDBController.js
│    ├── diagnosisDBController.js
│    ├── DispensingDBController.js
│    ├── generalDBController.js
│    ├── medicalRocordDBController.js
│    ├── medicalSuppliesDBController.js
│    ├── medicationDBController.js
│    ├── organizationDBController.js
│    ├── patientDBController.js
│    ├── statusDBController.js
│    ├── systemreviewDBController.js
│    └── userDBController.js
├── middleware
│    ├── verifyJWT.js
│    └── verifyRoles.js
├── model
│    ├── psychologist
│    │   ├── Psy_AppointmentDB.js
│    │   ├── Psy_CounselingRecorcdDB.js
│    │   └── Psychologist_PatientDB.js
│    │
│    ├── ActivitiesDB.js
│    ├── CheklistDB.js
│    ├── DiagnosisDB.js
│    ├── DispensingDB.js
│    ├── GeneralDB.js
│    ├── MedicalRecordsDB.js
│    ├── MedicalSuppliesDB.js
│    ├── MedicationsDB.js
│    ├── OrganizationsDB.js
│    ├── PatientsDB.js
│    ├── StatusDB.js
│    ├── SystemreviewDB.js
│    └── UserDB.js
│
├── router
│   ├── psychologistRouter
│   │    ├── psy_appoinmentRouter.js
│   │    ├── psy_counselingRouter.js
│   │    └── psy_patientRouter.js
│   ├── activitiesRouter.js
│   ├── authRouter.js
│   ├── checklistRouter.js
│   ├── diagnosisRouter.js
│   ├── dispensingRouter.js
│   ├── generalRouter.js
│   ├── medicalRocordRouter.js
│   ├── medicalsuppliesRouter.js
│   ├── medicationRouter.js
│   ├── organizationRouter.js
│   ├── patientRouter.js
│   ├── statusRouter.js
│   ├── sysyemreviewRouter.js
│   └── userRouter.js
│
└── util
    └── util.js


```
