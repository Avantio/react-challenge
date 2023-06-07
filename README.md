# Avantio React Challenge
Multi-Step Accommodation Creation Form.

## Main Goal
The main goal of this technical test is to develop a form for creating an accommodation.

The form consists of three steps, the first step is responsible for setting the accommodation data. The second step is responsible of the accommodation owner data. The last step is a summary of the two previous two steps.

We need a smooth transition between the steps and a random success/failure feedback message after submitting the form.

The components needs to be exported as CustomElement and fully integrated in the html attached `custom-form-result.html`, you can make the modifications that you consider to this file in order to make your component the more plug and play that you can.

![atrends](./doc/assets/form.png)

## Technical requirements
- You have to use React + Typescript combination.
- You must use TailwindCSS.
- We strongly recommend using of Redux for state management, we also use it in our components.
- The output of this component is a CustomElement (WebComponent).

## Expected functionality
The form will have three steps:
1. Accommodation data.
2. Owner data.
3. Summary of the form.

We can only have one step at a time in the screen, we should have to navigate between them.

In the first step we will ask for the accommodation data as: name, location, description, type and two pictures.

In the second step we will ask for the owner's details as: name, email and phone number.

In the third step we will display a summary of the previously submitted data and a random success/failure message or a validation error message, all the fields are required.

## Additional considerations
We strongly recommend following the best practices for React and TailwindCSS.

The design and position of the elements in the forms are up to you but we appreciate an intuitive and easy to use user interface.