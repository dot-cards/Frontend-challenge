# Frontend Challenge
An React focused take home challenge for Front-end Developers.
You will be building an admin dashboard for a made up e-commerce store. 
A admin should be able to create, delete, and sort the list of product cards. 
You should focuses on not only the functionality but design, usability and micro interactions. 

## Instructions 
- Clone this repository
- Complete this exercise and submit a link to the cloned repo.
- Using a tool like loom.com to record a brief demo of your submission. Submit a link to this recording.
    - Make sure to walk through the your design choices, any trade offs made, cross-browser compatibility, and responsiveness.
- Please use ReactJS. All other choices of libraries, frameworks, etc. are up to you. Our stack is NextJS with vanilla CSS.

## Requirements
- Product cards
    - We have provided a json file `dummyData.json` in the repository. This is what you will be using to render the product cards.
    - A product card consists of a products `title` `price` `description` `rating` `category`, and a list of images. All of these attributes should be displayed on the cards. 
    - The design and layout is completely up to you. We have provided a mockup of the form to create a product as reference to the design. We are looking for clean and concise CSS and HTML markup.
    - The card needs to be a pure react component. 

- Sort / filter product list
    - The product cards should be arranged in a grid. An info bar at the top with sort and filter input.
    - Add the functionality to sort the products by rating and by price.
    - Add the functionality to filter the products by category.
- Create a product
    - A simple form with the required product felids
        - `title` `description` `price` `rating` `category`
        - `id` is not part of the input list, it should be auto generated 
        - `image` file input is not required 
    - We have provided a mockup of what the input field should look like on mobile. Slide up draws are not idea for desktop, can you implement a better option for desktop users? 
- Delete a product
    - A button on the card to delete a product.
- Edit a product 
    - Editing the product is not required!
- Animation / Interactions
    - We are looking for a frontend designer that is passionate about micro interactions. 
    - Please add micro interactions / animations / transitions wherever to improves the user experience.
- Responsive Design 
    - Make sure the e-commerce admin dashboard is responsive across all screen sizes.
    - Make sure it is cross browser compatible. 
