**Name:-** BUGATHA RAJESH

**COMPANY:-** CODTECH IT SOLUTION

**ID:-** CT12DS2476

**DOMAIN:-** FRONTEND

**DURATION:-** SEPTEMBER 20th,2024 to NOVEMBER 20th,2024

**Mentor:-** Neel Santhosh Kumaar

## Project Name : INTERACTIVE QUIZ APPLICATION
This HTML code represents the structure of a simple quiz application, built using HTML, CSS, JavaScript, and Bootstrap. Here's an overview of the code:

## 1. HTML Structure
* The document starts with the <!DOCTYPE html> declaration for defining the document type.

* The html element has the lang="en" attribute, indicating that the document is in English.
* #### Head Section:
  * Metadata like charset, viewport, and compatibility settings for browsers are included.
  * The page title is set to "Javascript Quiz".
  * External CSS files are linked:
  * style.css (for custom styling),
  * Font Awesome (for icons),
  * Bootstrap CSS (for layout and design)
  * #### Body Section:

   * #### Header:
     * A header section with a bg-primary class (Bootstrap) to set a blue background.
     * It contains two title sections:
     * A left title with the word "Quiz".
     * A right title displaying the total number of questions (Total Questions: <span id="tque"></span>), which will be dynamically populated by JavaScript.
  * #### Quiz Content:
    * The main content of the quiz is wrapped in a <div class="content">.
    * Inside the content, there is a Bootstrap container (container-fluid), which ensures the content spans the full width of the screen.
    * The content contains a row (row), and inside it, a single column (col-sm-12), which contains the quiz question form.
  * #### Quiz Form:
    * The form is wrapped inside a <fieldset> for grouping related elements.
    * The current question is displayed with the following:
    * A question number (<span id="qid">1.</span>).
    * The question text (<span id="question"></span>), which will be filled dynamically by JavaScript.
    * A block for options (<div class="option-block-container" id="question-options"></div>), where quiz answer options will be inserted dynamically.
  * #### Two buttons are provided:
    * A "Previous" button (<button name="previous" id="previous" class="btn btn-success">Previous</button>), which allows the user to navigate to the previous question.
    * A "Next" button (<button name="next" id="next" class="btn btn-success">Next</button>), which lets the user move to the next question.
      
## 2. External Libraries:

  * **jQuery:** The code uses jQuery (via a CDN) to simplify JavaScript tasks like DOM manipulation and event handling.
  * **Bootstrap:** Bootstrap is used for responsive layout and styling, making the app mobile-friendly and visually appealing.
  * **Font Awesome:** Font Awesome is included for icons, although no specific icons are used in this code

## 3. JavaScript and Additional Functionality:

  * The page includes a reference to an external JavaScript file (script.js), which is likely where the quiz logic resides. This file would handle:
  * Populating the quiz questions dynamically.
  * Handling the navigation between questions (previous and next buttons).
  * Storing user responses and managing the quiz state (e.g., tracking the current question and user progress).
    
## 4. Interactivity and Dynamic Content:

  * The question and answer options are populated dynamically via JavaScript. For example:
  * The question text (<span id="question"></span>) will be filled with the current quiz question.
  * The options for the question will be added within the #question-options container.
  * The total number of questions will be dynamically displayed in the #tque span in the header.
    
### Summary:

This code outlines the basic structure of a JavaScript-based quiz application. It includes the layout, styling, and placeholders for dynamic content (questions and options). The functionality to handle user input, navigation, and displaying quiz data is expected to be implemented in the external script.js file. The use of Bootstrap ensures a responsive and attractive design, while jQuery helps with interactivity.

![Screenshot 2024-11-12 141649](https://github.com/user-attachments/assets/71afd490-e118-4b2d-aac0-a3f96358f18b)

![Screenshot 2024-11-12 140017](https://github.com/user-attachments/assets/391cc3f1-42d9-424c-ac32-5ab1043017a0)

![screencapture-rajeshbugatha-github-io-CODTECH-TASK2-2024-11-12-14_02_27](https://github.com/user-attachments/assets/2fc45276-32e4-4525-a6cd-03e32eccb3e7)

