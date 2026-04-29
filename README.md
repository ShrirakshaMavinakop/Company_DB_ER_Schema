
## E-R Diagram ### Company Data Storage Requirements

TECHIMPACKT:

The company is organized into branches. Each branch has a unique number, a name, and a particular employee who manages it.

The company makes it’s money by selling to clients. Each client has a name and a unique number to identify it.

The foundation of the company is it’s employees. Each employee has a name, birthday, sex, salary and a unique number.

An employee can work for one branch at a time, and each branch will be managed by one of the employees that work there. We’ll also want to keep track of when the current manager started as manager.

An employee can act as a supervisor for other employees at the branch, an employee may also act as the supervisor for employees at other branches. An employee can have at most one supervisor.
<img width="766" height="719" alt="Screenshot 2026-04-29 103028" src="https://github.com/user-attachments/assets/cff74b3c-cfd4-45ac-813c-f4c5523704ae" />


 Algorithem for Schema diagram

### seps1:-
	 Mapping of regular entity Type	for each regular entity type create a realtion type create a realtion (table)that  include all that includes the smile attributes of that entity

### Step 2: Mapping of Weak Entity Types:
	For each weak entity type create a relation (table) that includes all simple attributes of the weak entity

### Step 3: Mapping of Binary 1:1 Relationship Types: 
	Include one side of the relationship ##as a foreign key in the other Favor total participation

### Step 4: Mapping of Binary 1:N Relationship Types
	Include the 1 side's primary key as a foreign key on the N side relation (table)

### Step 5: Mapping of Binary M:N Relationship Types
	Create a new relation (table) who's primary key is a combination of both entites' primary key's. Also include any relationship attribtes
<img width="1024" height="575" alt="WhatsApp Image 2026-04-29 at 10 33 07 AM" src="https://github.com/user-attachments/assets/f9d24909-acab-4d06-abe8-983ef2faddd9" />
