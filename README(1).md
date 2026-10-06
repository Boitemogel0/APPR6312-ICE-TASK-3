# APPR6312 ICE TASK 3 -- Azure Repos and Source Control

## Student Management System

This project implements an ASP.NET MVC Student Management System and
demonstrates Git-based source control using Azure DevOps Azure Repos.

## 1. Project Overview

The application was developed as an ASP.NET MVC application using
Microsoft Visual Studio.

The purpose of the application is to provide a basic Student Management
System that allows users to manage student information through an MVC
web interface.

### Main functionality

-   View students
-   Add students
-   View student details
-   Edit student information
-   Delete students
-   Search/filter students
-   Form validation
-   Git-based version control
-   Azure Repos source-code management

## 2. Technology Stack

  Component               Technology
  ----------------------- --------------------------------------
  IDE                     Microsoft Visual Studio
  Application Framework   ASP.NET Core MVC
  Programming Language    C#
  Front-end               Razor Views / HTML / CSS / Bootstrap
  Source Control          Git
  Repository              Azure Repos
  DevOps Platform         Microsoft Azure DevOps

## 3. MVC Architecture

The application follows the Model-View-Controller architecture.

``` text
Student Management System
│
├── Models
│   └── Student.cs
│
├── Controllers
│   ├── HomeController.cs
│   └── StudentsController.cs
│
├── Views
│   ├── Home
│   ├── Students
│   │   ├── Index.cshtml
│   │   ├── Create.cshtml
│   │   ├── Details.cshtml
│   │   ├── Edit.cshtml
│   │   └── Delete.cshtml
│   └── Shared
│
├── wwwroot
│   ├── css
│   └── js
│
├── Program.cs
├── appsettings.json
└── StudentManagementSystem.csproj
```

## 4. Student Model

The `Student` model contains the following information:

-   Student ID
-   Student Number
-   First Name
-   Last Name
-   Email
-   Course
-   Year Level

Data-annotation validation is used for required fields, email validation
and year-level validation.

## 5. Student Management Controller

`StudentsController` provides the main application operations:

-   `Index()` -- displays and searches students
-   `Details()` -- displays a student's information
-   `Create()` -- creates a new student
-   `Edit()` -- updates an existing student
-   `Delete()` -- removes a student

## 6. Running the Application

### Prerequisites

Install:

1.  Microsoft Visual Studio with ASP.NET and web development support.
2.  A supported .NET SDK.
3.  Access to the Azure DevOps organization/repository.

### Steps

1.  Clone or open the project in Visual Studio.
2.  Restore the project dependencies if prompted.
3.  Build the solution using:

``` text
Build → Build Solution
```

or:

``` text
Ctrl + Shift + B
```

4.  Run the application using:

``` text
Ctrl + F5
```

5.  Open the Students page:

``` text
/Students
```

## 7. Git and Azure Repos Workflow

The project follows this source-control workflow:

``` text
Create MVC Application
        ↓
Initialize/Connect Git
        ↓
Initial Commit
        ↓
Push to Azure Repos
        ↓
Make Change 1
        ↓
Commit and Push
        ↓
Make Change 2
        ↓
Commit and Push
        ↓
Make Change 3
        ↓
Commit and Push
        ↓
Verify Azure Repos Commit History
```

## 8. Azure DevOps Repository

The project repository is hosted in Azure DevOps Azure Repos:

**Azure DevOps Repository:**

https://ST10448828@dev.azure.com/ST10448828/APPR6312%20ICE%20TASK%203/\_git/APPR6312%20ICE%20TASK%203

## 9. Required Git Commits

The implementation uses separate commits for the initial application and
each meaningful change.

### Initial Commit

``` text
Initial MVC Student Management System
```

This commit represents the initial version of the MVC application.

### Change 1

``` text
Add student CRUD functionality
```

This change introduces the main student management CRUD operations.

### Change 2

``` text
Add validation and improve student interface
```

This change improves input validation and the application's user
interface.

### Change 3

``` text
Add student search functionality
```

This change introduces student searching/filtering.

## 10. Git Implementation Process

### Initial commit

After creating the MVC application:

1.  Open **Git Changes** in Visual Studio.
2.  Review the modified/untracked files.
3.  Stage the required files.
4.  Enter:

``` text
Initial MVC Student Management System
```

5.  Select **Commit All**.
6.  Push the commit to Azure Repos.

### Change 1

1.  Implement student CRUD functionality.
2.  Test the application.
3.  Open **Git Changes**.
4.  Enter:

``` text
Add student CRUD functionality
```

5.  Commit.
6.  Push.

### Change 2

1.  Add validation and interface improvements.
2.  Test the application.
3.  Open **Git Changes**.
4.  Enter:

``` text
Add validation and improve student interface
```

5.  Commit.
6.  Push.

### Change 3

1.  Add student search functionality.
2.  Test the application.
3.  Open **Git Changes**.
4.  Enter:

``` text
Add student search functionality
```

5.  Commit.
6.  Push.

## 11. Expected Commit History

The Azure Repos commit history should demonstrate a progression similar
to:

``` text
Add student search functionality
        ↓
Add validation and improve student interface
        ↓
Add student CRUD functionality
        ↓
Initial MVC Student Management System
```

This demonstrates incremental source-code development and version
control.

## 12. Azure Repos Verification

After pushing the changes, verify the repository in Azure DevOps.

Check:

-   Repository files
-   Commit history
-   Commit messages
-   Different versions/changes
-   Final source-code version

## 13. Assessment Evidence

The project documentation should contain evidence for the following:

1.  Azure DevOps project created.
2.  Azure Repos Git repository created.
3.  MVC application in Visual Studio.
4.  Visual Studio connected to Azure Repos.
5.  Initial Git commit.
6.  Initial push to Azure Repos.
7.  Change 1 and its commit.
8.  Change 2 and its commit.
9.  Change 3 and its commit.
10. Azure Repos commit history.
11. Final repository.

Each screenshot should be accompanied by a short explanation stating
what was done and what the screenshot demonstrates.

## 14. Recommended Evidence Captions

### Figure 1 -- Azure DevOps Project

Demonstrates that the Azure DevOps project for APPR6312 ICE Task 3 was
successfully created.

### Figure 2 -- Azure Repos Repository

Demonstrates that the Git repository was created in Azure Repos.

### Figure 3 -- MVC Application

Demonstrates the Student Management System project and MVC structure in
Visual Studio.

### Figure 4 -- Repository Connection

Demonstrates that the Visual Studio project is connected to Git/Azure
Repos.

### Figure 5 -- Initial Commit

Demonstrates the initial Git commit of the MVC application.

### Figure 6 -- Initial Push

Demonstrates that the initial commit was pushed to Azure Repos.

### Figure 7 -- Change 1

Demonstrates the first meaningful application change and its separate
Git commit.

### Figure 8 -- Change 2

Demonstrates the second meaningful application change and its separate
Git commit.

### Figure 9 -- Change 3

Demonstrates the third meaningful application change and its separate
Git commit.

### Figure 10 -- Azure Repos Commit History

Demonstrates the chronological history of the initial commit and the
three subsequent changes.

### Figure 11 -- Final Repository

Demonstrates the final source-code version stored in Azure Repos.

## 15. Final Verification Checklist

Before submission, verify:

-   [ ] ASP.NET MVC application created.
-   [ ] Application runs successfully.
-   [ ] Student functionality implemented.
-   [ ] Azure DevOps project created.
-   [ ] Azure Repos Git repository created.
-   [ ] Visual Studio connected to the repository.
-   [ ] Initial commit completed.
-   [ ] Initial commit pushed.
-   [ ] Change 1 implemented.
-   [ ] Change 1 separately committed and pushed.
-   [ ] Change 2 implemented.
-   [ ] Change 2 separately committed and pushed.
-   [ ] Change 3 implemented.
-   [ ] Change 3 separately committed and pushed.
-   [ ] Repository files visible in Azure Repos.
-   [ ] Commit history visible.
-   [ ] Commit messages visible.
-   [ ] Different versions demonstrated.
-   [ ] Final repository verified.
-   [ ] All required screenshots captured.
-   [ ] Every screenshot has an explanation.

## 16. Conclusion

The project demonstrates the development of an ASP.NET MVC Student
Management System and the use of Git with Azure DevOps Azure Repos for
source-code management.

The development process demonstrates:

``` text
ASP.NET MVC Development
          ↓
       Git Tracking
          ↓
        Commit
          ↓
         Push
          ↓
     Azure Repos
          ↓
   Version History
          ↓
   Final Repository
```

The repository provides a central location for the application's source
code and preserves the development history through separate Git commits
for the initial implementation and subsequent meaningful changes.

------------------------------------------------------------------------

## Repository Link

https://ST10448828@dev.azure.com/ST10448828/APPR6312%20ICE%20TASK%203/\_git/APPR6312%20ICE%20TASK%203
