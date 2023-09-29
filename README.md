CMPG 323 Project 4 - Intelligent Data Analytics Platform
Table of Contents

    - Overview
    - Prerequisites
    - Implementation Options
    - Requirements
        GitHub Administration
        Project Setup
        User Acceptance Testing
        UI Automation
        Record Results
        Project Close-out
    - Reading Materials
    - Community Engagement
    - Certification
    - Submission Details

# Overview

Welcome to Project 4 of CMPG 323! This project focuses on the integration of Robotic Process Automation (RPA) into the user acceptance testing (UAT) phase of software development. UAT is a critical step in ensuring that a solution functions as expected before it is deployed to production. In this project, we will leverage RPA to automate repetitive testing tasks, making the UAT process more efficient and accurate.
Prerequisites

Before you dive into this project, make sure you've completed the following prerequisites:

    UiPath Automation Cloud Account: Ensure you have created a UiPath Automation Cloud account, which will be used for RPA development and management.

    UiPath Studio Community Edition: Download and install UiPath Studio Community Edition on your computer. This is your development environment for creating RPA workflows.

    Access to Web Application: You should have access to the web application that you'll be performing UI automation on. In this project, we'll use the web application hosted at https://cmpg323-ecopowerlogistics.azurewebsites.net/.

    Test Data: Retrieve the Excel file containing the test data that will be used during UAT.

# Implementation Options

For this project, our primary focus is on adapting the UiPath solution for RPA testing. The web application used in Project 3 is hosted for your convenience, but you won't have access to the Azure resources or the database. Please concentrate on the UiPath RPA implementation.
Requirements

Here's a breakdown of the project's functional requirements and tasks:
GitHub Administration

    Create and Configure GitHub Repository:
        Create a repository named 'CMPG 323 Project 4 - <add your student number>'.
        Create a ReadME.md file to describe your project and guide stakeholders on how to use the report you develop.

    Project Progress:
        Commit and push your solution to source control throughout the project.
        Update the GitHub project iteratively to demonstrate project progress.

# Project Setup

    Create the Project:
        Clone your GitHub repository.
        Install UiPath Studio.
        Create a new UiPath process named 'Connected Office Web Application – User Acceptance Testing'.

# User Acceptance Testing

    Read the input data:
        Read the data from Excel into a data table in UiPath.
        Ensure the data is readable and can be iterated over in UiPath.

# UI Automation

    Automate UI Testing:
        For each record in the data table, navigate to the web application's URL to create a new record.
        Insert the fields from each record into the web application's fields.
        Click the 'submit' button on the web application to create a new record.
        Navigate to the URL where you can view the newly created record on the web application.

# Record Results

    Record Testing Results:
        If the item was created successfully, update the data table record to indicate that the record passed testing.
        If the item was not created, update the data table to depict that the record failed testing.
        Update the Excel spreadsheet with the testing results (Test Results column of the provided Excel file – update with TRUE or FALSE).

# Project Close-out

    Deploy Solution:
        Publish the UiPath solution to the UiPath Orchestrator.

    Project Documentation:
        Ensure that the ReadMe.md file in the GitHub repository explains how users should use the report.
        Create a reference list document containing all sites visited and used during the project.

# Reading Materials

To assist you with this project, consider referring to the following resources:

    Introduction to RPA and Automation
    UI Automation with UiPath
    Excel Automation with UiPath

# Community Engagement

Don't hesitate to engage with the UiPath community if you encounter challenges or wish to explore the possibilities of UiPath further. You can join relevant LinkedIn groups, visit Stack Overflow, participate in the UiPath Community Forum, attend UiPath Meetups, or follow YouTube UiPath Influencers.
Certification

If you find RPA intriguing and wish to obtain a UiPath certification, explore the training and the UiPath RPA Associate Developer certification to advance your skills.
Submission Details

This project is an individual assignment, and GitHub is a crucial part of it. Please ensure your repository is set to private and only shared with designated markers.

# Submission Deadline: 17:00 on 19 October 2023 (no alternative or late submission dates).

What to submit:

    Provide the URL to your GitHub Repository.
    Provide the username of the user used to add data to the database through the web application.
    Provide proof that your process has been published to the UiPath Orchestrator.
    Include your reference list file in Harvard referencing style.
