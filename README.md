# Frontend Challenge
A React focused take home challenge for Front-end Developers.
You will be building an admin dashboard for a made up e-commerce store. 
The admin should be able to create, delete, and sort the list of product info cards. 
You should focus on not only the functionality but design, usability and micro-interactions. 

## Instructions 
- Clone this repository
- Complete this exercise and submit a link to the cloned repo.
- Using a tool like loom.com to record a brief demo of your submission. Submit a link to this recording.
    - Make sure to walk through the your design choices, any trade offs made, cross-browser compatibility, and responsiveness.
- Please use ReactJS. All other choices of libraries, frameworks, etc. are up to you. Our stack is NextJS with vanilla CSS.

## Requirements
- Product info cards
    - We have provided a json file `dummyData.json` in the repository. This is what you will be using to render the product cards.
    - A product card consists of a products `title` `price` `description` `rating` `category`, and a list of images. All of these attributes should be displayed on the cards. (Only need to use a single image)
    - The design and layout is completely up to you. We have provided a mockup of the form to create a product as reference to the design. We are looking for clean and concise CSS and HTML markup.
    - Please keep OOP principles in mind. 

- Sort / filter product list
    - The product cards should be arranged in a grid. An info bar at the top with sort and filter input.
    - Add the functionality to sort the products by rating and by price.
    - Add the functionality to filter the products by category.
- Create a product
    - A simple form with the required product felids
        - `title` `description` `price` `rating` `category`
        - `id` is not part of the input list, it should be auto generated 
        - `image` file input is not required 
    - We have provided a mockup of what the create product draw should look like on mobile. Slide up draws are not idea for desktop, can you implement a better option for desktop users? 
- Delete a product
    - A button on the card to delete a product.
- Edit a product 
    - Editing the product is not required!
- Animation / Interactions
    - We are looking for a frontend designer that is passionate about micro-interactions. 
    - Please add micro interactions / animations / transitions wherever to improves the user experience.
- Responsive Design 
    - Make sure the e-commerce admin dashboard is responsive across all screen sizes.
    - Make sure it is cross browser compatible. 
## Rubric
The first thing we are looking for is your thought process. We want to see how you approach problems. Don't be afraid to change approaches in the middle. That might mean a lot of commits. If you just do one big commit at the end, all of your thought process is lost.

The second is polish. That means in terms of functionality, but also in terms of code. In between can be messy, but your final commit should be demonstrating what you consider to be ready for production.

The specification of the functionality is specifically designed to force you to make some design trade-offs. Be prepared to explain and defend the choices you make.

These are the specific things we are looking at:

- Functionality - Does it work? Does it meet all the needs as outlined in the specification?
- Documentation - Is there a way to know what endpoints to hit? Are they clear and accurate?
- Tools - Is the tooling appropriate to the problem? How well does it use the chosen tools? Does it follow best practices of the framework?
- Style - Is there a clear separation of concerns? Does it reuse code where possible? Does it look good?
- Commits - Is there a clear commit history to follow?
