   Patient Information Database System		
Hospitals require pertinent patient data in order to Provide the best possible care. This can be extremely beneficial to healthcare professionals and hospital administrators when it comes to treating patients. One approach to collect all of this data is to construct a database that not only stores previous medical records but also stores data when a new patient enters. With this information, healthcare practitioners may keep track of patient information that can be referred to when the need arises, as it can be utilized for a variety of purposes. Along with the old medical records, we intend to include information about doctors, diseases, medications, and equipment.

Since it is a very complex structure, we would be modelling just a portion and we have applied some limitations in the system.
•	To keep things simple, we are not considering any global pandemics 
•	We are assuming all patients who visit the hospital are having health insurance 
•	We are limiting number of appointments allowed to book per day and same number of appointments will be present all the time. 
•	We are limiting our DB system so that the time slot which patient has booked will be used to complete his entire treatment all the way from doctor check-up to billing.
•	Doctor will update the patient health records at the time of visit.
•	We are not including pricing details for the treatment and will have only standard appointment fees
•	We are limiting our system so that every patient will visit the hospital at the time of appointment and cannot cancel the appointment
•	We are reducing the number of specializations of only five namely common illness, cardio, ortho, Neuro and General surgeon
Data Requirements:
Patients:
•	Each patient will have a unique membership ID 
•	New Membership ID will be created if patient is new to the hospital
•	Every patient will have name, date of birth, gender, phone number, email ID and address
•	If patient is already registered in the system, then he will use the same old ID
•	Only one booking is allowed for a person in a day

Appointments:
•	Patient will receive unique ID of the appointment at the time of booking
•	Date and time of booking will be included in the appointment
•	Patient symptoms

Doctor will be assigned based on the symptoms provided at the time of booking and no preferences of doctors are allowed. The old patient’s data is already present in the system so he is assigned to the doctor directly.
Specialization:
•	Specialization ID and name
•	Doctor ID and name
•	Patient ID
•	Specialization description
Once appointment is confirmed, system will assign the patient to the doctor with the corresponding specialization based on the provided symptoms.
Doctor:
•	Every doctor will have name, ID, phone number, email ID and gender
•	Specialization ID and specialization name of doctor 
•	Each doctor will have username and password to access patient information
Once the patient approaches the doctor with all his medical tests, doctor will assess the medical condition and provides the prescription based on the illness of the patient. 

Medical records:
•	Patient details 
•	Patient ID and a unique OR(old record) ID
•	Details of previously used medicines 
•	Details of the diseases which affected patient
The purpose of keeping a medical record is to share information about a patient's care with other healthcare professionals, and it is also the only way for a doctor to prove that the treatment was done correctly. The database was created with the goal of reducing paper work in the administrative area, as well as the time spent by patients waiting for their files to be retrieved.

Disease:
•	Disease ID and name
•	Each disease has different symptoms
•	Description of disease
Generally, there are five types of illness and these include common illness, cardio issues, neuro, ortho and General internal issues.
Prescription:
•	Prescription ID and patient details
•	Medicine details
•	Doctor Id and name
•	Date and time
Doctor logs the prescription to the patient which includes details of the treatment and medication by assessing his test records. Medicines are offered 
Medicine:
•	Medicine ID and name
•	Doctor prescription will contain medicine name based on the disease
•	Medicine description
•	Patient name and ID

Functionalities: 
•	How many new patients are being registered in the system?
•	How to Manage time slots and availability of doctors?
•	How frequent a specific medicine is sold in a targeted month?
•	What Symptoms are being reported for maximum number of times?
•	Any relation between time of the year and the disease?
•	Which specialization has minimum and minimum number of appointments based on symptoms?
•	How many patients’ health is deteriorating based on the age?
•	How many patients are regularly visiting the hospital?

Objectives & Goals:
•	Having these medical records, hospital can respond promptly in treating and alerting patients during public health crisis.
•	The reports generated through medical records can be shared to the medicine manufacturing companies to justify the demand (Patient personal details will not be shared here)
•	Based on the current data we can obtain average time required to treat a patient and predict the outcome for the future 
•	Report will be provided to the government for the doctor scarcity in particular specialization
•	Based on the data we can predict the frequent diseases which are affecting different age groups and act accordingly and share the information to NGO’s and various organizations.
•	Medical records which are saved can be shared with government and various charities so that patients may have a high chance of getting financial aid 
•	We can take precautionary measures by identifying seasonal diseases in people.
