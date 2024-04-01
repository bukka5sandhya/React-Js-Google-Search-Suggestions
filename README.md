In this project, let's build a Google Search Suggestions app by applying the concepts we have learned till now.

Refer to the image below:

![image](https://github.com/bukka5sandhya/React-Js-Google-Search-Suggestions/assets/133884532/ab215fb8-a8b4-4faa-960a-fd72b3ac3c00)

https://assets.ccbp.in/frontend/content/react-js/google-search-suggestions-output.gif

Design Files

Click to view

Extra Small (Size < 576px) and Small (Size >= 576px)

Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)

Set Up Instructions

Click to view

Download dependencies by running npm install

Start up the app using npm start

Completion Instructions

Functionality to be added

The app must have the following functionalities

Initially, all suggestions in the suggestionsList should be displayed

When a value is provided in the search input, then display the suggestions which includes the search input irrespective of case

When the arrow of a suggestion is clicked, then the value of the search input should be updated with the respective suggestion clicked

The GoogleSuggestions component receives the suggestionsList as a prop. It consists of a list of suggestion objects with the following properties in each suggestion object

Key	Data Type
id	Number

suggestion	String

Components Structure

![image](https://github.com/bukka5sandhya/React-Js-Google-Search-Suggestions/assets/133884532/72f3359c-8f3a-4fc7-ac4e-f91fed17cd5e)

Implementation Files

Use these files to complete the implementation:

src/components/GoogleSuggestions/index.js

src/components/GoogleSuggestions/index.css

src/components/SuggestionItem/index.js

src/components/SuggestionItem/index.css

Quick Tips

Click to view

You can use the box-shadow CSS property to apply the box-shadow effect to containers

box-shadow: 0px 4px 16px 0px #bfbfbf;

![image](https://github.com/bukka5sandhya/React-Js-Google-Search-Suggestions/assets/133884532/b9ff8b23-d16f-4b48-b908-c097c696e078)

You can use the cursor CSS property to specify the mouse cursor to be displayed when pointing over an element

 cursor: pointer;


![image](https://github.com/bukka5sandhya/React-Js-Google-Search-Suggestions/assets/133884532/0d77bf64-2ab1-4c7e-9dc6-15de302b00a1)


You can use the below outline CSS property for buttons and input elements to remove the highlighting when the elements are clicked

 outline: none;

Resources

Image URLs

https://assets.ccbp.in/frontend/react-js/google-logo.png alt should be google logo

https://assets.ccbp.in/frontend/react-js/google-search-icon.png alt should be search icon

https://assets.ccbp.in/frontend/react-js/diagonal-arrow-left-up.png alt should be arrow

Colors

Hex: #bfbfbf

Hex: #64748b

Hex: #475569

Font-families

Roboto

Things to Keep in Mind

All components you implement should go in the src/components directory.

Don't change the component folder names as those are the files being imported into the tests.

Do not remove the pre-filled code

Want to quickly review some of the concepts you’ve been learning? Take a look at the Cheat Sheets.
