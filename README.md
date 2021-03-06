# ETL Project

In this assignment, you will put your ETL skills to the test by migrating data from a cloud MySQL database, hosted on Amazon Web Services (AWS) to a Salesforce application that you will build. This is a practical, real-world example of data movement.

Although you will be working as a team, each team member should set up their own MySQL database, their own Salesforce environment, migrate their own data, and submit their own Salesforce application and code.

The following outlines what you need to do.

### Before You Begin

1. Be sure that your MySQL database is set up on AWS

2. Ensure that you have created your Salesforce developer account

3. Set up your Trailhead account on Salesforce and connect it to your developer account

## Step 1 - Database Setup

Ensure that your MySQL database has been set up and that the GWSIS objects have been created. Be sure to also load the data tables. We completed these steps as a class during Week 13.

## Step 2 - Salesforce Trails

Complete the following trails on Salesforce to familiarize yourself with the platform:
* Platform Development Basics: https://trailhead.salesforce.com/content/learn/modules/platform_dev_basics
* Data Modeling: https://trailhead.salesforce.com/en/content/learn/modules/data_modeling

## Step 3 - Salesforce Application Setup

You will be utilizing what you have learned up to this point to build a Student Information System on the Salesforce platform. Work with your team to design the architecture for the system.

Include the following tables at minimum:
* Student
* Course
* Class
* Class Participant
* Staff
* Staff Assignment

Be sure to produce an entity relationship diagram (ERD) from MySQL workbench to illustrate the database structure.

You may also get creative and utilize some of the standard objects within Salesforce. This is optional.

## Step 4 - Data Movement (ETL)

Develop an ETL process in Python that loads each of the tables in Salesforce from your MySQL database on AWS. See the starter code for inspiration.

## Resources

Be sure to reference the `simplesalesforce` documentation. You can find more information here: https://github.com/simple-salesforce/simple-salesforce

## Submission

First, you will need to grant `dwilliams4@2u.com` access to your Salesforce org. 

1. From within Setup, type in Users into the Quick Find box
2. Click the Users link from the Quick Find result
3. From the Users page in the All Users panel, click the New User button
4. On the New User screen, complete the form but the following fields are important:
    *   Email: dwilliams4@2u.com
    *   Username: dwilliams4.[your-first-name]@2u.com (the username has to be unique, so you can place .[your-first-name] after dwilliams4)
    *   User License: Salesforce
    *   Profile: System Administrator
5. Once you have completed the required fields, click the Save button at the bottom of the screen.

To submit your work to BootCampSpot, please do the following:

1. Grant `dwilliams4@2u.com` access to edit your Salesforce org
2. Create a new folder for the ETL project in your homework repository
3. Load your Jupyter Notebook and other code to the folder and push up the changes
4. Submit the link to your repository to BootCampSpot

### Copyright

Data Boot Camp © 2020. All Rights Reserved.