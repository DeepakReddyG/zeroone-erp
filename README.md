# zeroone-erp
##Project Description
-------------------------------------------------
user levels: Members, Mentors and Admins


Database Design:
1. users (sno, id, name, primary email, personal email, gender, branch, year, username, password(hashed passowrd)); 
2. members list (sno, id)
3. mentors list (sno, id)
4. admins list (sno, id)
5. members_pro_dashboard(sno, id, languages, projects, research, proScore)




-----------------------------------------------------------------------
*Student level:
          1.Profile(contact information)
          2.Attendance
          3.Exams
          4.Time table(schedule)
          5.Material/links (separate folder)/submissions
          6.Registrations for upcoming events
	      7.Feedback

*Mentor level:
          1.Time table for mentors
          2.profile(contact detalis)
          3.Calender
          4.Students remarks
	      5.CRUD on assigned students. 

*Admin level:
(Access the all the students data)
        1.About club president and contact detalis
        2.All students data
        3.verification students detalis
	    4.Content Management: Manages and updates content on the ERP system, such as           
	      announcements and resources.
        5.Security and Access Control
	    6.Backup and Data Recovery
	    7.Settings and configuration.




