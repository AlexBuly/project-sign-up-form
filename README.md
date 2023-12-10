# project-sign-up-form

In this project, the task is to create a sign-up form for an imaginary service. The page contains a background imagine, header, and a form with inputs for first name, last name, password, and password confirmation. Below the form, there is a button to mock creating the account and a section to log in if the user already has an account. 

First, a fieldset was created so that all elements within the form can be grouped together.

The next task was to add the form inputs. The tricky part was how to get the input rows put together in block display. The solution was to create each row as flex items, so 6 flex items total. 

Next, in order for the inputs work on smaller display I added a media query for when the width is smaller than 1000px. Within the media query, each row is now at block-level display and the padding within the form is decreased to avoid items becoming misplaced on the page. 

Finally, styling and form validation took place. When "required" is added to the HTML inputs, it means that the forms cannot be submitted unless that field is filled out. The email has a special input type that does not submit the form unless the @ sign is included and a ".". 

Regular expressions were added to the phone and password inputs to only allow the user to enter a phone number with dashes and only allow the user to create a secure password. 

Placeholders were also added to show the required formats of certains inputs. 