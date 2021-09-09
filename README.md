# MARKETING AGENCY MOCKUP: CODE REFACTOR

## DESCRIPTION
Web accessiblity is a very important aspect of web design as it ensures that all people regardless of their language, location or ability, are able to have clear access to websites using assistive technologies.

Accessibility is also very good for businesses as more accessible websites tend to rank higher in search engines.

For this assignment, I was given existing code to refactor (improve upon without changing what the code does) to meet a set of standards and make a website more accessible.

## User Story
A marketing agency wants a codebase that follows accessiblity standards so that their site is optimised for search engines.


## What Was Done and How Did It Solve The Issue
The existing HTML code did not contain proper semantic elements and predominately used <div>'s instead. I modified the code to add semantic elements such as <header>, <section>, <main> and <footer> to keep the code looking more clean.

The header links were only working for 2 of the three sections within the main body. It was found that only two of them contained id attributes. An id was added to the third to make sure that all the links not only worked, but went to the right sections of the main body.

The images within the HTML code were not given any alt attributes so I added one to describe what was in each image.

The website was also plainly titled 'website' so this was changed to 'Horiseon marketing agency'.

-----

The existing CSS code was not in a structured order, so I modified it to be placed in the order that the content flowed within the HTML.

I also added comments to the CSS code, describing what each section did and the code was also consolidated to make it easier to comprehend.


# Final Comments
Through this task I learned more about how important semantic elements and CSS coding structure are as they make sure everything is simplified and easier to read for not only the next coder, but also the viewer of the webpage. I also learned how crucial accessiblity is to not only businesses but costumers as well. Web design should always be user-friendly.

