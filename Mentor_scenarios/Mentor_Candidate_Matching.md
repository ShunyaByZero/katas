# Capability - Matching of Mentor to Candidate

## Features

### Mentor to Candidate Matching 
 ***
 **The Platform will not automatically assign the Mentor to Candidate but it will aid or help the Candidate or Mentor to search each other**
 
### Candidate to Mentor Matching Engine

  - As soon as Candidate creates a profile with his requirement, this usecase will be triggered 
  - A Platform will check the Candidate requirement on skill and check the current avilable Mentors 
	  - Skill /Expertise Match
	  - Mentor location 
	  - Mentor should have avilable capacity to help Candidate
	  - The Platform will inform all the Qualified Mentors to choose the Potential Candidate
	  
### Mentor Selcting a Candidate 
 - Mentor can select the Candidate based on the Enginee recomendation
 - When the Mentor select a Candidate
	 - Platform will reduce the Capacity parameter of the Mentor
	 - Platform will make the Candidate status as assigned for that specific skill
	 - Platform will send an email to Mentor and Candidate about the assignment 
	     

### Candiate Drops from mentorship
 - When the Candiates decides to drop the mentorship
	 - Platform will increase the Capacity parameter of the Mentor
	 - Platform will make the Candidate status as unassigned/droped for that specific skill
	 - Platform will send an email to Mentor and Candidate about the assignment 
	 - Adminstrator will remove the candidate from the Mentorship

  
### Candiate change the  mentor

 - When the Candiates decides to change the mentorship
 	 - Platform will increase the Capacity parameter of the Old Mentor
	 - Platform will decrease the Capacity parameter of the New Mentor
	 - Platform will make the Candidate status as change of the Candidate
	 - Platform will send an email to Mentor and Candidate about the assignment 
	 - Adminstrator will remove the candidate from the Mentorship

### Tracking the UnAssigned Candidate 
 - Candidate may not get any Mentor based on the current situation
 - When the Candidate may not have any mentor assigned more than one week
 - The email communication will go to the Platform Administartor
 - Platform Administartor can help the Candidate offline 
	  
