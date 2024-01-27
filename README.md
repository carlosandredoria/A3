# Assignment 3 - Simple "Hello, World!" Windows Forms Application

## Overview

In this assignment, you will create a straightforward Windows Forms application using C# and Visual Studio. The goal is to introduce you to the basics of designing a graphical user interface (GUI) and handling user interactions within a Windows Forms application.

## Task

### Task Description

Your task is to build a basic Windows Forms application that displays a "Hello, World!" message when a button is clicked. This assignment serves as an introductory exercise to cover the following key concepts:

- Creating a Windows Forms project in Visual Studio.
- Designing a user-friendly UI by adding controls (specifically, a button).
- Implementing event handlers to respond to user actions.

### Step-by-Step Instructions

Follow these step-by-step instructions to complete the assignment:

#### 1. Create a Windows Forms Project

1. Open Visual Studio.

2. Navigate to "File" > "New" > "Project...".

3. Select "Windows Forms App (.NET Framework)" as the project template.

4. Name your project and choose a location to save it.

5. Click "Create" to initiate the project.

#### 2. Design the User Interface (UI)

1. In the Solution Explorer, double-click the Form (e.g., `Form1.cs`) to open the Form Designer.

2. Utilize the designer to drag and drop a Button control onto the Form.

3. Double-click the Button to select it and modify its Text property to "Click Me!"

#### 3. Implement Button Click Event

1. Double-click the button on the form. Visual Studio will automatically generate a button click event handler for you.

2. Within the generated event handler code, insert the following code to display a message box with the "Hello, World!" message when the button is clicked:

   ```csharp
   private void button1_Click(object sender, EventArgs e)
   {
       MessageBox.Show("Hello, World!");
   }
