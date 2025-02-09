# MealPrepHub
MealPrepHub is a meal prep website that provides users with healthy and delicious recipes that can be prepared quickly and easily. The website is aimed at people who wish to maintain a healthy diet without spending a lot of time cooking. MealPrepHub offers a wide range of recipes that are designed to be easy to prepare and packed with nutrients. Macros are provided for each recipe to make it easy for the users to track ank keep up with their respective caloric intake. The website also provides tips and tricks for meal prepping, making it easy to plan your meals for the week ahead.

[MealPrepHub Link](hhttps://joelchan13.github.io/mealprephub/)

![Responsive Mockup](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/mealprephub-mockup.png?raw=true)

## Features

- ### Navigation
  - Featured at the top of the page with the project logo on the left of the navigation bar, which also serves as a link to the homepage. The right side of the navigation section features a link to the homepage, a link to the recipe list, and a link to the sign up page.
  - When accessed through a mobile device, the navigation links on the right side of the respective section feature in a drop down menu

![Navigation Desktop View](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/navigation-desktop.png?raw=true)

![Navigation Desktop View](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/navigation-mobile.png?raw=true)

### Header
- The header features the project logo, and the mission slogan.
- The same colour scheme was used for this section, with orange as a background colour for the text, and mint as the main font colour.

![Cover Text](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/cover-text.png?raw=true)

### Recipe List
- The recipe list section provides the user the ability to select recipes based on their prep time, cook time, and difficulty. These details are included in the selection pane of each recipe.
- By clicking the respective recipe, the user will be directed to the corresponding recipe.
- The same background image used for each recipe in the recipe list was used for the respective recipe page.
- A background colour was added to the text to facilitate ease of raadability.

![Recipe List](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/recipe-selection.png?raw=true)

### Recipes
- The recipe pages feature an image of the recipe at the top of the page, below the navigation section.
- The recipe title, along with the macro nutrients, feature on top of the recipe image. In order to create a contrast, an orange background colour was used to ensure better readability.
- Below the recipe image, the user can also find the prep time, cook time, and difficulty featured in the recipe list section.
- The ingredients and instructions are divided into two sections, whereby the ingredients feature in an unordered list, whilst the instructions feature in an ordered list.
- In the mobile view, the instructions sit below the ingredients list, whilst in desktop view, the instructions and ingredients sit side by side.

![Recipes](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/recipe.png?raw=true)

### Sign Up
- The sign up section provides the users with a form to submit their details in order to sign up to MealPrepHub.
- The form collects the user's first name, last name, and email address.
- Upon successful submission of the details, the user is greeted with a confirmation page, thanking the user for their submission.

![Sign Up Form](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/sign-up-submission.png?raw=true)

![Sign Up Confirmation](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/sign-up-greeting.png?raw=true)

## Testing
- The page was tested on multiple browsers, including Firefox, Chrome, Brave, Edge, and Safari.
- The project is responsive and fully functional in all standard screen sizes.
- Testing was conducted to ensure ease of readability on different devices.

### Validator Testing
#### HTML
- No errors were returned when testing all sections of the project through the W3C validation.
#### CSS  
- No errors were returned when testing styling section of the project through the W3C validation.
#### Accessibility
- Testing was done through Lighthouse DevTool and the result was satisfactory
![Lighthouse Validation](https://github.com/JoelChan13/mealprephub/blob/main/assets/images/lighthouse-validation.png?raw=true)
#### Functional Testing
| Action  | Expected Outcome  | Pass/Fail |
| :------------ |:---------------:| -----:|
| Click on project logo | Go to Homepage/index.html        |    Pass |
| Click on Home from Navigation bar | Go to Homepage/index.html and underlines Home link in navigation bar        |    Pass |
| Click on Recipes from Navigation bar | Go to Recipe List Page/recipes.html and underlines Recipes link in navigation bar        |    Pass |
| Click on Sign Up from Navigation bar | Go to Sign Up Page/sign-up.html and underlines Sign Up link in navigation bar        |    Pass |
| Press the burger favicon from Navigation bar in mobile view | Opens drop-down list with Home, Recipes, and Sign Up links        |    Pass |
| Click on the Facebook favicon in the footer section | Opens new tab and directs user to Facebook webpage        |    Pass |
| Click on the Instagram favicon in the footer section | Opens new tab and directs user to Instagram webpage        |    Pass |
| Click on the YouTube favicon in the footer section | Opens new tab and directs user to Instagram webpage        |    Pass |
| Click on Spicy Chicken Popcorn recipe bar from the Recipe Page/recipes.html | Directs user to the Spicy Chicken Popcorn Recipe/spicy-chicken-popcorn.html and underlines Recipes link in navigation bar        |    Pass |
| Click on BBQ Beef Meatballs recipe bar from the Recipe Page/recipes.html | Directs user to the BBQ Beef Meatballs/bbq-beef-meatballs.html and underlines Recipes link in navigation bar       |    Pass |
| Click on Peanut Butter Protein Granola recipe bar from the Recipe Page/recipes.html | Directs user to the Peanut Butter Protein Granola Recipe/pb-protein-granola.html and underlines Recipes link in navigation bar       |    Pass |
| Click on Protein Cinnamon Rolls recipe bar from the Recipe Page/recipes.html | Directs user to the Protein Cinnamon Rolls Recipe/protein-cinnamon-rolls.html and underlines Recipes link in navigation bar       |    Pass |
| Submit empty Sign Up form | Presents error message prompting user to fill in the required fields whilst highlighting the border of the respective fields in red       |    Pass |
| Submit form without first name | Present error message promting user to submit first name whilst highlighting the border of the respective field in red       |    Pass |
| Submit form without last name | Present error message promting user to submit last name whilst highlighting the border of the respective  field in red       |    Pass |
| Submit completed form | Field border changes from red to black and user taken to confirmation page/confirmation.html        |    Pass |
| Hover over submit button from desktop view| submit button changes colour        |    Pass |
| Hover over Home link on the navigation bar | Underlines Home link in navigation bar        |    Pass |
| Hover over Recipes link on the navigation bar | Underlines Recipes link in navigation bar        |    Pass |
| Hover over Sign Up link on the navigation bar | Underlines Sign Up link in navigation bar        |    Pass |
| Access recipes from mobile device | Ingredients section sits above the Instructions section        |    Pass |

## Deployment
- The site was deployed to GitHub pages. From the GitHub repository, access mealprephub. Click on the deployments section. Click on the active deployment link provided.
- [MealPrepHub Link](https://joelchan13.github.io/mealprephub/)
- Migrated on VSCode on 9th February 2025

### Local Deployment
- The repository was clones to local machine using the following command in your terminal: git clone <https://github.com/JoelChan13/mealprephub.git>
- The following command was submitted in the terminal: cd mealprephub.
- index.html was opened in the browser to start website.

## Credits

### Content
- The code to formulate the social media links was taken from the CI Love Running Project
- Boilerplate HTML Structure Code was taken from the ci-full-template found in CI GitHub repo by lechien73

### Media
-The images used for this website were generated using Microsoft Bing Image Creator powered by DALL·E 3.