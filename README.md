## Overview
This OpenRPA robot, titled “Reports Download” is designed to automate the process of logging into a web application, navigating through various project sections, downloading reports, and closing tabs upon completion. The workflow is structured as follows:

1. **Login Sequence**: The robot starts by logging into the application using the provided URL, username, and password.

2. **Project Selection**: It navigates to a given project name.

3. **Report Download Sequences**: The robot then goes through multiple sequences to download different types of schedules:
– **Area Schedule**
– **Fixture Schedule**
– **Zone Schedule**
– **Control Schedule**
– **Equipment Schedule**

For each type of schedule, it:
– Opens the respective schedule page.
– Clicks the download button to save the report.
– Closes the tab after downloading the report.

4. **Logout**: After downloading all the reports, the robot logs out of the application.

This automation aims to streamline the process of accessing and downloading various reports from the specified project within the web application, ensuring efficiency and consistency in handling repetitive tasks.


## Demo
<img src="https://github.com/TunahanBoyaci/Automated-Report-Download-Workflow-for-Project-Management/blob/main/src/-.gif">

