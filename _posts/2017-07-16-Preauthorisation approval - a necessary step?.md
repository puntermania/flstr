Preauthorisation approval is a process where the patient through provider seeks a prior approval from the payer for receiving certain types of care, medication or treatment from the provider. If the preauthorisation approval is not requested before receiving specific categories of procedures then payer may refuse to pay for those procedures or medications thus increasing burden on patient to pay for treatment. There is also a danger of increased bad debt for providers, in case the patient is unable to pay for the treatment for which preauthorisation approval was not requested.

Through preauthorisation, the payer determines and validates the medical necessity and aptness of the procedure prescribed by the provider. Preauthorisation approval helps payer keep a tab on healthcare costs by preventing duplicate and unnecessary services, while offering patients generic alternatives, if available. Preauthorisation is also leveraged by providers to cover the risk of non-payment when patient insists on payer coverage. 

Preauthorisation can be mandated by the payer for any of the following:
1. Admission to hospital - emergency or non-emergency inpatient
2. Referral to a specialist
3. Performing specific categories of service
4. Prescribing specific categories of medicines even when generics are available

Imagine visiting a Dentist, who is within payer’s network, for half-yearly dental checkup. Most dental insurance policies offer two cleanings in a year. During such visit, the dentist examines and detects deep cavities on molars, which requires root canal treatment (RCT) and crowns. Per the dental insurance policy, preauthorisation from payer is required before provider performs RCT and cements crown. The provider contacts the payer to confirm the need of the preauthorisation. If preauthorisation is required then provider with the help of coder sends the preauthorisation request along with necessary patient health information to payer in X12 278 file format version 5010. The payer sends a response acknowledging receiving the preauthorisation form in X12 278 file format. The payer or third-party administrator (TPA) then reviews the preauthorisation request form and contacts the provider or patient in case more information such as X-Rays, charts, notes etc. is required. After the decision has been made, the payer communicates the decision to the provider in X12 278 file format. Until the decision is made, the provider is free to reach out to payer to know the status of preauthorisation. The payer responds with ‘pending’ or ‘need more review’ response until the final decision is made on the request. 

Following are the key information required while requesting preauthorisation approval:
1. Patient Details
2. Ordering Physician Details
3. Rendering Patient Details
4. Type of Service
5. Type of Procedure
6. Type of Device(s) being used
7. Additional details on procedure
8. Whether the request in emergency, non-emergency or elective
9. ICD-10 code of the primary procedure
10. Planned date of the procedure
11. Site where the procedure/service will be provided (Office, Outpatient Hospital, Ambulance, Home, Inpatient etc.)

If there are more procedures or services for which preauthorisation approval is requested then information from 4 (Type of Service) to 11 (Site of Service) are repeated for each service or procedure.

The outcome of the preauthorisation are any of the following:
1. approved in full, i.e. all prescribed services can be provided to the patient
2. approved in part, i.e. only a few among all prescribed services can be provided to patient per policy. The reason for denial of other prescribed services is also provided by the payer in the response
3. denied, i.e. no authorisation is provided for the prescribed services. If patient and provider still go ahead with the prescribed services then payer will not be covering or remitting or reimbursing any monies for those services

With the denial, the payer can insist the patient go through an intermediate ‘fail first’ process, wherein a provider and patient must first see unsuccessful results from a generic or alternative, yet cheaper, service preferred by the payer. Only after the ‘fail first’ treatment or service has failed, the payer will provide the preauthorisation approval.  

Preauthorisation approval has been deemed as extremely burdensome by 387 of the 400 providers that kclstr reached out to. Typically a provider and his/her staff spend over 1.8 hours a day in preauthorisation process, a valuable time which should be spent on treating patients otherwise.  On an average it takes 5-7 days to receive preauthorisation approval, and until then patients and providers are held back on treatments and follow-ups fearing mounting healthcare costs. An instant preauthorisation approval system will ensure that no patient has to wait more than a few seconds to seek any treatment that is necessary for patient’s wellbeing. It is also important to simplify and standardise the preauthorisation across payers so that time to complete the preauthorisation process can be less than two minutes.
