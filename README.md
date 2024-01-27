# Simple "Hello, World!" Windows Forms Application

## Overview

In this assignment, you will create a simple Windows Forms application using C# and Visual Studio. This exercise is designed to introduce you to the basics of designing a graphical user interface (GUI) and handling user interactions in a Windows Forms application.

## Task

### Task Description

Your task is to create a basic Windows Forms application that displays a "Hello, World!" message when a button is clicked. This assignment will help you become familiar with the following concepts:

- Creating a Windows Forms project in Visual Studio.
- Designing a user interface (UI) by adding controls (in this case, a button).
- Implementing event handlers to respond to user interactions.

### Step-by-Step Instructions

Follow these steps to complete the assignment:

1. **Create a Windows Forms Project:**
   - Open Visual Studio.
   - Go to "File" > "New" > "Project...".
   - Select "Windows Forms App (.NET Framework)" as the project template.
   - Give your project a name and choose a location to save it.
   - Click "Create" to create the project.

2. **Design the User Interface (UI):**
   - In the Solution Explorer, double-click the Form (e.g., `Form1.cs`) to open the Form Designer.
   - In the designer, drag and drop a Button control onto the Form.
   - Double-click the Button to select it, and in the Properties window, change its Text property to "Click Me!"

3. **Implement Button Click Event:**
   - Double-click the button on the form. Visual Studio will generate a button click event handler for you.
   - In the generated event handler code, add the following code to display a message box with the "Hello, World!" message when the button is clicked:
     ```csharp
     private void button1_Click(object sender, EventArgs e)
     {
         MessageBox.Show("Hello, World!");
     }
     ```

4. **Test Your Application:**
   - Build and run your application by clicking the "Start" button in Visual Studio.
   - When you click the "Click Me!" button, a message box should appear with the "Hello, World!" message.

### Conclusion

By completing this assignment, you will have created a simple Windows Forms application and learned the basics of designing a GUI and handling user interactions in Visual Studio. This is a great starting point for your journey into Windows Forms development.

Feel free to explore further and customize your application's UI and functionality as you gain more experience. Have fun with your "Hello, World!" Windows Forms app!
