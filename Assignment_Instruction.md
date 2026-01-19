# GitHub & Xcode Setup + Hello World App (100 points)

Submission: GitHub Classroom repository link (Canvas)

## Assignment Overview

This first assignment is designed to ensure that your development environment is set up correctly before we move on to iOS programming concepts.

In this assignment, you will:

- Use GitHub Classroom to accept an assignment

- Use GitHub Desktop to manage a project repository

- Make commits and push changes to GitHub

- Install and verify Xcode

- Build and run a simple Hello World iOS app

**Note**: This assignment is about **setup and workflow**, not advanced coding.


## Learning Objectives

By completing this assignment, you will be able to:

- Use GitHub Classroom to manage course assignments

- Clone and manage repositories using GitHub Desktop

- Commit and push changes to GitHub

- Create and run an iOS app using Xcode and the iOS Simulator

- Verify that your system is ready for future coursework

## Assignment Tasks
### Part A: GitHub Classroom & README Setup (40 points)
**Step 1:** Accept the GitHub Classroom Assignment

- Click the GitHub Classroom link provided in Canvas: https://classroom.github.com/a/7VNyklC4

- Log in using your GitHub account (MU email required)

- Click **Accept Assignment**

- Wait for your **private repository** to be created

**Step 2:** Clone the Repository (GitHub Desktop)

- Click **Open in GitHub Desktop**

- Choose where to save the project on your computer

- Open the repository in GitHub Desktop

**Step 3:** Update README.md

Open the README.md file and add the following information:

```
Name: Your Full Name
Course: INFOTC 4405 / CMP_SC 4405
Section: In person / Online
Semester: Spring 2026
```

Save the file.

**Step 4:** Commit and Push

In GitHub Desktop:

- Enter a commit message such as:  ``` "Update README with student information" ```

- Click **Commit to main**

- Click **Push origin**

- This completes **Part A.**

### Part B: Xcode Hello World App (60 points)

**Important Before You Start**: you must create the Xcode project **inside your GitHub Classroom repository folder on your local machine** so it is tracked automatically.

**Step 5:** Create an iOS App in Xcode

1. Open Xcode

2. Select **Create a new Xcode project**

3. Choose:

    - Platform: **iOS**

    - Template: **App**

4. Click **Next**

5. Project Settings: set the following:

    - **Product Name**: HelloWorldApp
    - **Interface**: Storyboard
    - **Language**: Swift

6. When Xcode asks where to save the project:

    - Navigate to your **GitHub Classroom repository folder on your local machine**

    - Example: HW1-GitHub-Xcode-Setup

    - Save the project **inside this folder**

7. Click **Create (The Xcode project is now part of your GitHub repository.)**


**Step 6:** Modify the App (change the Label Text to “Hello, iOS!”)

- Open Main.storyboard

- Select label from the library by pressing (Press ⇧ Shift + ⌘ Command + L ) to open 
library window
- Select label from the library by pressing (Press ⇧ Shift + ⌘ Command + L ) to open library window

- Drag the label inside the View Controller (phone Scene)
- Change the label text to: Hello, iOS!  from (Attributes Inspector/ change the label)

**Step 7**: Run the App

- Choose an iOS Simulator device

- Click Run ▶

- Confirm the app runs successfully in the simulator

**Step 8**: Take a Screenshot

- Take a screenshot showing:
    - The simulator running

    - The “Hello, iOS!” text visible

- Save the screenshot as: yourPawPrint_screenshot.png

**Step 9**: Commit & Push All Project Files and app screenshot

- Place yourPawPrint_screenshot.png in the **root folder** of your GitHub repository

- When you open **GitHub Desktop**, you should see **multiple files listed as changes**, including:
    - The **Xcode project folder** (many files)
    - yourawPrint_screenshot.png

- Commit with a message such as: "Add Hello World app & the screenshot"

- Push your changes to GitHub

Expected Repository Structure:

    HW1-YourUsername/
    ├── README.md
    ├── sourPawPrint_screenshot.png 
    └── (Xcode project files)

## Submission Instructions

1. Make sure all changes are committed and pushed to GitHub

2. Copy the repository URL

3. Submit the repository link in Canvas

**Note:** Uploading files directly to Canvas is **not accepted**
