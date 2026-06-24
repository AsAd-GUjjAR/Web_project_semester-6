# Job Skill Gap Analyzer -- Resume Builder

## Overview

Job Skill Gap Analyzer is a web-based application that helps job
seekers: - Find suitable jobs based on their skills - Identify missing
skills for a target job role - Discover learning resources for skill
improvement - Generate a professional resume instantly

## Features

### Skill Gap Analysis

Compare user skills with job requirements and identify missing skills.

### Job Finder

Suggests suitable job roles based on the user's skills.

### Resume Builder

Create and download a professional CV by filling out a simple form.

### Database Storage

Save user profile and resume information for future use.

### Trending Courses

Provides learning recommendations for missing skills.

## Problem Statement

Many job seekers face the following challenges: - Lack of awareness of
in-demand skills - Difficulty comparing their skills with job
requirements - Trouble creating professional resumes - Need to use
multiple platforms for jobs, courses, and resumes

## Solution

This project combines: - Job recommendations - Skill gap analysis -
Learning resources - Resume generation - Database storage

All in one platform.

## Target Users

-   Students
-   Fresh Graduates
-   Job Seekers
-   Career Switchers
-   Freelancers
-   Career Counselors

## Example Skill Analysis

**User Skills** - HTML - CSS

**Target Job** - Web Developer

**Required Skills** - HTML - CSS - JavaScript - React - Bootstrap

**Missing Skills** - JavaScript - React - Bootstrap

## Technology Stack

  Layer          Technology
  -------------- -------------------------
  Frontend       HTML5, CSS3, JavaScript
  Backend        PHP
  Database       MySQL
  Local Server   XAMPP / Apache

## Architecture

User → Browser → HTML/CSS/JavaScript → PHP → MySQL Database

## Tools Used

-   VS Code
-   XAMPP
-   Google Chrome
-   Git

## Project Structure

``` text
home.html          # Main page
skill.html         # Skill analysis page
job.html           # Job finder page
profile.html       # Resume builder
stylesheet.css     # Styling
save_cv.php        # Database operations
```

## Database

### Database Name

`cv_database`

### Table Name

`cvs`

  Column       Type
  ------------ --------------
  id           INT
  name         VARCHAR(100)
  phone        VARCHAR(20)
  email        VARCHAR(100)
  skills       TEXT
  education    TEXT
  experience   TEXT
  created_at   TIMESTAMP

### CRUD Operations

-   Create
-   Read
-   Update
-   Delete

## Validation Rules

-   No empty fields
-   Email must contain `@`
-   Phone number must be 11 digits

## Main Pages

-   Home
-   Skill Analysis
-   Job Finder
-   Resume Builder
-   About Us

## Benefits

-   Free to use
-   Browser-based
-   No installation required
-   Simple and lightweight
-   Professional CV generation
-   Skill improvement guidance

## Conclusion

Job Skill Gap Analyzer provides a complete solution for students and job
seekers by combining: - Skill Gap Analysis - Job Recommendations -
Course Suggestions - Resume Building - Database Storage

## Team Members

-   M Asad Qayyum
-   Hanzla Saleem
-   Asif Shabbir
-   Saad Hassan
