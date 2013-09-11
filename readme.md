# What is this?

This is data that was scraped from the McGill website / Minerva using the scraper I built at the first HackMcGill hackathon. 
The data was scraped on _September 10th, 2013_.

# Courses

Courses are stored in courses\_{type}\_{semester}.json. Currently it only has Undergraduate courses for Winter 2014. 

Structure:
	
	{
		"name": "Course name",
		"shortname": "Course short name (code and number)",
		"link": "Direct link",
		"faculty": "Faculty name",
		"department": "Department name",
		"credits": "Number of credits or 'Unavailable'"
	}


# Course Locations

Course locations are stored in courses\_locations\_{type}\_{semester}.json
_Still need to explain the structure for this_.

# Faculties & Departments

These are just stored as an array of strings in _faculties.json_ and _departments.json_ respectively.

