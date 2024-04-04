### Team Name:

21479 Group 3

### Team Members:

Harrison Goldstein: <br>
Fiza Bhayani: <br>
Ethan Denbrok: <br>
Luke Lambert: <br>
Raul Fernandez:  

### Problem Description:



### Data Model: 

<img width="623" alt="Screenshot 2024-04-04 at 3 23 29 PM" src="https://github.com/lhl88422/lhl88422/assets/150093821/80387ee1-d93d-4166-a051-ae22b07556c9">

### Explanation of data model:
This data model encapsulates a robust system designed to efficiently manage operations within a tennis club, encompassing various facets ranging from member administration to court reservations, event coordination, payments, feedback collection, coaching, and league management.

Fundamentally, the model captures comprehensive member profiles, including personal particulars, membership status, and their engagement within the club such as court reservations, event participation, payments, and feedback. This enables personalized interactions and streamlined monitoring of member activities, ensuring a tailored experience for each individual within the tennis club community.

Moreover, the model accommodates staff roles pivotal in court management, event organization, coaching sessions, and overall club oversight. Staff members are allocated specific responsibilities, facilitating tasks like court maintenance, event planning, and scheduling coaching sessions, thereby ensuring the smooth functioning of day-to-day operations.

Furthermore, the model facilitates the management of tennis courts, equipment, and leagues within the club. Members can easily reserve courts for practice or matches, with coaching sessions led by certified instructors. Leagues are structured with teams formed by club members, fostering a spirit of competition and community. Additionally, events hosted by the club can be seamlessly integrated with tournaments through a one-to-one recursive relationship, enhancing the club's versatility and providing opportunities for competitive play within the tennis community.

### Data Dictionary: 
<img width="671" alt="table 1" src="https://github.com/lhl88422/lhl88422/assets/150093821/ea3f2185-2052-43c0-a9f5-aab180d04070">

<img width="685" alt="table 2" src="https://github.com/lhl88422/lhl88422/assets/150093821/9677a1d3-7622-418d-9c98-d761b87b4a62">

<img width="710" alt="table 3" src="https://github.com/lhl88422/lhl88422/assets/150093821/a4cccf5c-6643-4a37-888f-3d6f174051f7">

<img width="689" alt="table 4" src="https://github.com/lhl88422/lhl88422/assets/150093821/344d9da2-71bc-4bf5-a924-e3190eafae0e">

<img width="502" alt="table 5" src="https://github.com/lhl88422/lhl88422/assets/150093821/16eab923-2425-4434-bd69-328dc94397b7"> <br>

<img width="498" alt="table 6" src="https://github.com/lhl88422/lhl88422/assets/150093821/25d3584d-44e5-48f6-9e77-f5b94bf8ee38">

<img width="527" alt="table 7" src="https://github.com/lhl88422/lhl88422/assets/150093821/49f42553-5dd4-425d-8639-3479f7fcc8ea">

<img width="518" alt="table 8" src="https://github.com/lhl88422/lhl88422/assets/150093821/d4ed4110-f70d-43d7-bd79-79bde31ef62c">

<img width="512" alt="table 9" src="https://github.com/lhl88422/lhl88422/assets/150093821/9ccc3bde-3168-469d-bca9-c21c062b301b">

<img width="533" alt="table 10" src="https://github.com/lhl88422/lhl88422/assets/150093821/655f0f33-ae43-49f1-97de-30ad323b4a41">

<img width="515" alt="table 11" src="https://github.com/lhl88422/lhl88422/assets/150093821/481f808d-78f0-4d45-ab7d-34825108d967">

<img width="528" alt="table 12" src="https://github.com/lhl88422/lhl88422/assets/150093821/75edfb47-bb8c-46f2-a0fe-c80ad9c2dab2">



### Queries: 
Query 1:<br>

Justification: This is helpful information for the facilities to have for resource allocation and to ensure that they are appropriately managing their employee's workload. <br>


Query 2:<br>

Justification: This information is helpful as it can be used for quality assessments for every facility and can be helpful when conducting performance evaluations in order to ensure customer satisfaction. <br>

Query 3:<br>

Justification: This is useful information that can be used for financial tracking as well potential reward/recognition of committed members to the facilities. <br>


Query 4:<br>

Justification: This can be useful information for session planning on the coach/staff members end as well as resource allocation within their own facility as well as across all facilities. This information is also useful in equipment management and ensuring all of the equipment purchased is accounted for. <br>

Query 5:<br>

Justification: Having the ability to pull a team captain name based on filters up to the discretion of the data analyst allows dor the ability to improve communication, ensure leadership recognition and improve decision-making by having the information be readily available. <br>

Query 6:<br>

Justification: This information allows the facilities to send targeted communication strategies to ensure all members have access/ability to create a reservation to ease their time at our facilities. <br>

Query 7:<br>

Justification: This information can be used for the coaches performance evaluation,workload management and resource allocation. <br>

Query 8:<br>

Justification: This information is useful in order for scheduling purposes of staff and coaches as well as resource management. This information is also useful to track member engagement. <br>

Query 9:<br>

Justification: This information can be used for revenue maximization, resource allocation, customer retention and optimizing the company's competitive advantage and assessing it’s operational efficiency. <br>

Query 10:<br>

Justification: This information allows us to understand which tournaments have a more rigorous work schedule as staff salary is based on work completion.<br>

### Database Information:
Name of the database: al_Group_21479_G3 <br>
<br>
Additional information: Query 7 and 9 listed above is marked in the database using stored procedures which can be called using the following format: “ CALL GetCoachTrainingSessionCounts7(); “ and “CALL GetReservedFacilities9();”





