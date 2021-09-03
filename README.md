# Studio 8080 Clothing Co. Customer Survey

## Overview

A customer survey for a mock business in the fashion industry. Sleek and minimalistic UI.

## Description

The purpose of this project was to create a survey form that fulfills the following user story:

```md
GIVEN a survey form and repository
WHEN I view the source code
THEN I see a title with id="title" in H1 sized text, and a short explanations with id="description" in p-sized text
WHEN I view the source code
THEN I see a form element with id="survey-form" with input fields of various types
WHEN I fill out the survey
THEN I see that name and email are required fields, and I have to submit a valid email format
WHEN I fill out the survey
THEN I see a number input with a min and max and HTML validation
WHEN I view the source code
THEN I see that the input fields in the form have corresponding labels
WHEN I view the name, email, and number input fields
THEN I see informative placeholder text
WHEN I fill out the survey
THEN I see a dropdown question, a multiple choice question with radio buttons, a question with a series of checkboxes, and a textarea at the end for additional comments
WHEN I am finished with the survey
THEN there is a submit button with id="submit" on the page
```

Because survey forms are such an essential part of customer and employee feedback, I took this opportunity to consider a minimalistic and user-friendly UI for a business in the fashion industry. I chose the name Studio 8080 because port 80 is the port number most often used for HTTP requests. :)

It was interesting to research the various questions that are best to ask customers. While there are many ways to analyze data through Google Ads/Google Analytics and similar tools, there are certain questions that can only be answered through a direct customer survey. This was an excellent opportunity for me to reflect on what I've learned in my Google Ads certification and determine how to use these tools together to ultimately maximize conversions and customer satisfication.

When I first started learning how to code in HTML and CSS, I did not realize how much validation already exists by specifying particular input types in forms. Certain inputs need to be checked through JavaScript and customized regular expressions, but HTML form validation alone can certainly handle inputs such as emails. I wish I would have recognized that earlier on as a developer because it would have saved me more time (and kept previous web applications even more lightweight).

I took this opportunity to practice using a background image with a tinted overlay and glassmorphism. Initially I tried to create a light overlay for the background image, but realized that changing the opacity would also affect how the text displayed on the page. By using a linear gradient and background image, I was able to preserve the correct opacity for child elements. Using a glassmorphism style for the form container helped create an even more minimalistic and elegant UI.

Overall, I am excited about what I learned in building this page and look forward to applying these concepts in future projects.

Please find the deployed page here: https://vruss14.github.io/studio-8080-customer-survey

## Technologies Used

- HTML
- CSS
- Google Fonts

## Installation

No installation steps are required to view this project. To view the page, visit the URL above. The application's source code can be found on GitHub here: https://github.com/vruss14/studio-8080-customer-survey.

## Usage

This page is a simple survey form powered by HTML and CSS. It does not intend to represent a real business. The page includes responsive design strategies and can be viewed on all devices.

Below is a screenshot of the desktop version of the deployed page:

![screenshot of webpage for desktop]()

Below is a screenshot of the deployed page on mobile:

![screenshot of webpage for mobile]()

## Credits

Valerie Russell was the sole contributor to this project. Contact her at vruss14@gmail.com.

### References

* [Background image by Nataliya Vaitkevich from Pexels](https://www.pexels.com/photo/person-in-brown-button-up-shirt-4641825/)
