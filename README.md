# CKEditor-Challenges-GHW-Beginners-Week-2025

Hi Hackers! CKEditor is a great open source tool that allows users to create and edit web content within a browser, and so much more! <br><br>
If you're looking for a great way to make your development projects more robust, CKEditor is a great way to get started. 

## Getting Help 

* If you have any questions about CKEditor or their Global Hack Week challenges, head to the [MLH Discord](https://discord.mlh.io/) and find the #ask-CKEditor channel!
* Each challenge is accompanied by helpful documentation

# Challenges

## Challenge 1
### Signup for a CKEditor account

#### Objectives: 
* Head over to the CKEditor [sign up page](https://mlh.link/ghwbeginner25-ckeditor-signup) to create an account and obtain the trial license key.
* In the CKEditor Customer Portal, navigate to the License keys tab to obtain your trial key.
* Submit a screenshot of your new account on our day-of [GHW form](https://mlh.link/ghwform)! 

## Challenge 2 
### Use Builder to create a starter project

#### Objectives: 
* Go to the Builder: Open the [CKEditor Builder](https://mlh.link/ghwbeginner25-ckeditor-builder) to start customizing your editor.
  * Select a Preset: Choose the Classic Editor preset as the foundation for your project.
* Pick Features:
  * The preset includes pre-selected features.
  * Enable additional features manually from the list to meet your needs. Avoid including the following features because these are relevant for the following challenges: Code Block, Templates, and Merge Fields. 
* Customize the Toolbar: Customize the toolbar for an optimal experience.
* Download the project:
    * Follow the setup steps provided by CKEditor Builder to generate the starter project. Specify Vanilla JS as technology and self-hosted as an integration method
* Share your implementation with us on our submission form and bonus points if you add your project to our [Devpost Page](https://mlh.link/ghwdevpost)! 


## Challenge 3 
### Add and configure the code block plugin
#### Objectives: 
* Enhance your editor to support code blocks

* **Steps to Complete:**
  1. Install the Plugin: Add the Code Block plugin to your CKEditor configuration.
      * Use the CodeBlock plugin import from the ckeditor5 package.
      * Add it to your plugins array in the configuration and items array of the toolbar.
  2. Customize the Plugin:
      * Define the programming languages you want to support. Each language should have a language and label properties.
* Share your implementation with us on our submission form and bonus points if you add your project to our [Devpost Page](https://mlh.link/ghwdevpost)! 

## Challenge 4 
### Add and configure templates
#### Objectives: 
* Implement templates for creating reusable document structures. 

* **Steps to Complete:**
  1. Enable the Template Plugin: Add the template plugin by importing it from the ckeditor5-premium-features package.
  2. Include Templates to the Editor Setup: Add it to your plugins array in the configuration and items array of the toolbar.
  3. Define Templates:
      * By creating the _definitions array_, define the templates you want to use.
        * Each template should have the following:
     	    * **title** - short description of the template
     	    * **description** - longer description
     	    * **data** - a string that contains the HTML structure of a template
* Share your implementation with us on our submission form and bonus points if you add your project to our [Devpost Page](https://mlh.link/ghwdevpost)! 

## Challenge 5
### Add and configure merge fields
#### Objectives: 
* Use merge fields to insert reusable content dynamically

* Steps to Complete:
  1. Enable Merge Fields: Add the MergeFields plugin by importing it from the ckeditor5-premium-features package.
  2. Include Merge Fields to the Editor Setup: Add it to your plugins array in the configuration and items array of the toolbar.
  3. Define Merge Fields:
      * By creating the _definitions array_ inside the _mergeFields configuration_, define the merge fields you want to use.
        * Each one should have:
   	      * **id**
   	      * **label**
          * **defaultValue**
  4. Use Merge Fields in templates: By using the id in the template, incorporate Merge Fields in your templates.
* Share your implementation with us on our submission form and bonus points if you add your project to our [Devpost Page](https://mlh.link/ghwdevpost)! 
