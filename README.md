#AngularTest

Create a page depicting a form designer, where a user can create a custom field from the default field types available and dynamically display a form

#Getting Started

Change directory into angular-test and write the command ng-serve --open The project will run on the localhost:4200

#Prerequisites

Install Node package npm install / npm i

#Installing
The npm start command builds (compiles TypeScript and copies assets) the application into dist/, watches for changes to the source files, and runs lite-server on port 4200. Shut it down manually with Ctrl-C.

#INSTALLING THE CODE

The following are detailed instructions for installing the code so you can code.

Ensure you have node installed.

At a command prompt, type node -v to ensure you have version 10.16.0 or higher before proceeding.

Download or clone the code from this repository.

If you download as a zip file, be sure to unzip it.

There should be a package.json file in this folder.

In a command window (or the Command prompt in VS Code), type npm install.

This creates a node_modules folder and installs all packages from the package.json file into that folder. You may see a few warnings during this process, but you should not see any errors.

In the same command window (or the Command property in VS Code)

The application should then compile and launch in your default browser.

If these steps don't work for you, see STACKBLITZ below.

#Locations
 component is in the zip file
  There are three components which is form component, Preview component and update componnet
  -form component : 70% left side of the page and shows empty table with headers, a preview button and add button. 
  -Update omponent: 30% right side of the page and shows a form as shown in above picture 
  -Preview Component: To display the actual form created. 
 
 Add/Update form is in template form validation
 Preview form is in Reactive form validation
 
 #Expectation:
 -In the form component there is an empty table with the add field button will be able to create one table. Just check the unique Id       before saving the details of form.
 -After saving the all required fields will appear the details in the table which is in the left side of the window.
 -with the help of preview button choose the unique Id and the form details will appear in the popup window.
 -As per the need user can change the particular details with required fields and submit the form. 
 -Changed can be seen in the table.
 
