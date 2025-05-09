# Brightspace Student Course Experience Survey (SCES) Information
This plugin is used to inform students and instructors about the Student Course Experience Survey (SCES) configuration for thier program and Brock University. The web page/plugin will provide students with a link to the survey and instructors links to their optional tasks to configure the survey.

Brock University's Student Course Experience Survey's configuration varies across the 100+ programs at Brock University that participate out of the 140+ programs that offer courses at Brock University. This plugin will provide students with a link to the survey and instructors links to their optional tasks to configure the survey. The web page/plugin also communicates to instructors about the configuration of their program and the survey's, who the Centre for Pedagogical Innovation (CPI) thinks is the contact in their department. Most importantly, the web page/plugin will provides everyone with a consitent path to surveys and survey results.

# Installation:

Upload all files to the Brightspace "Public Files" area. For this example we're using "Plugins/SCESabout" as the location. This is path will be needed later.

Brock University hosts the JSON files for configuration of the survey in a seperate web application, but this plugin assumes it is contained in Brightspace itself.

# Create 2 Custom Links:

First Link:
- Name: Course Survey (This title will be shown in a Navbar for instructors to create new schedules)
- URL: https://{YOUR_BRIGHTSPACE_DOMAIN}/shared/Plugins/SCESabout/SCESabout.html
- Behaviour: Same window
- Availability:
	- Share with child org units
	- Limit to specific roles
		- Select all roles that should create schedules (not students)
- Save

# Acknowledgements

Thanks to mattdig for the initial code and appraoch to the scheduler tool that inspired this plugin. This plgin is a fork of Matt's scheduler tool in tribute to his work, despite the fact that it is not a scheduler tool.