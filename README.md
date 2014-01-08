arrogant-seagull
================

That's one arrogant seagull.

------------

What's the plan?
------------

The main idea is to have an online system allowing to store the courses notes instead of the sempiternel xls file.

The project should have those different features:

* Online mysql database.
* The php database config file holding the identification to it will be replaced by a dummy in this repository. I mean by that a fully functional file, but without actual user, password and that kind of shit. Commit it once, then block it in .gitignore or something like that.
* Allow different users (user name & password).
* No minimum security on the password.
* A user can only see his notes.
* A user with administration privileges can manage courses.
* Admin can add, delete, edit a course.
* A course has those properties:
	* Name.
	* Identifier (like INFO-F-404).
	* Note field.
	* ECTS.
	* Note of the course.
* Note fields are the different way of adding a note to a course (exam, project, etc.) and has the following properties:
	* Denomination.
	* Note.
	* Percentage of the total note.
	* Max of the note.
* Global mean note.
* Ideally, I would see a system allowing to determine the note needed to pass a course. For example, we have 15/20 at 60%, what is the minimal we need to score on the last 40% to have at lease 10/20 for the course? We could have a system of sliders (remember the system used at DSight for the decision problems).
* Export user profile as csv.

First, I need to make some UML diagrams for the database and the general structure of the project.
