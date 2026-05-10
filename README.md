#   <img width="80" height="72" alt="Image" src="https://github.com/user-attachments/assets/1a58dc3d-044f-4874-9c5a-bdf2ae5fedcc" />  MedRoute
An LLM Router based chat bot performing OPD administration tasks using google sdk

Problem:
 1. Doctors lose valuable patient-care time handling billing and data entry (EHR/PACS) during routine visits.
 2. Patients frequently forget required medical records, resulting in delayed care and return visits.
 3. Current systems rely on single, expensive models that are prone to errors (hallucinations) from handling too many tasks at once.


It uses a fast, intelligent routing layer to analyze incoming requests and delegates the actual work to a fleet of specialized, task-bound agents. 
1. LLM Agent(Route agent): Routes the query to respective model
2. EHR Agent: Access,analyze ,and retrieve medical from FHIR servers
3. Billing Agent : reviee clinical notes and suggest accurate medical codes for faster billing
4. PACS Agent : Same as EHR agents but analyze medical images such as X rays ,CT etc


# LLM FRAMEWORK
<img width="600" height="290" alt="Image" src="https://github.com/user-attachments/assets/d146335f-9248-4583-9f74-10145028c5a8" />
