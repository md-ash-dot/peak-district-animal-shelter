# PEAK DISTRICT ANIMAL SHELTER

The Peak District Animal Shelter website is a landing page for members of the public looking to find out about who we are and what we do.

Users of this webiste will be able to find out about what we do for animals, how they can play a part in all of it, when they can meet the animals, fill out a contact form so they can be reached out to and also getting information on where to find us, our contact details etc.

![Responsive mockup](/assets/images/screens.JPG)

## FEATURES

### EXISTING FEATURES

- **NAVIGATION**
  - The navigation is featured on the top of the page, with the name on the top left: PEAK DISTRICT ANIMAL SHELTER, that also links to the top of the home page.
  - The other navigation links are on the top right: Home, Animals, Contact.
  - The Home navigation link brings you back to the home page from any page of the website.
  - The Animal navigation link takes you to a different page where the animal photos are featured.
  - The Conatct navigation link takes you to a different page where a conatct form and find us at details are featured.
  - The navigation can clearly show the name of the website and all other pages that the users can navigate to easily from any of the pages of the website.
![Navigation screenshot](/assets/images/Navigation.JPG)

- **LANDING PAGE**
  - The landing page displays a hero image below the navigation.
  - The hero image is an image of a closeup photo of a cat. The image is animated using @keyframe, the image shows the animation effect on loading of the page.
  - There is a welcome message with three points Rescue, Love and Repeat, which floats on top of the hero image.
![Landing page hero image](/assets/images/Landing-hero.JPG)

- **WHAT WE DO SECTION**
  - The what we do section has thee parts, explaining what we do explained with short paragraphs.
  - The three parts Animal Rescue, Shelter & Care and Adoption services are layed out next to each other to show at first glance about things we primarily do, telling the users about us.
![What we do section](/assets/images/what-we-do.JPG)

- **ANIMAL MEETING TIMES**
  - The animal meeting times section has a header inviting the general public to come meet our animals.
  - There are four days on when the animals can be met at specific times, this can be understood by users on first glance of the section.
  - The days, time and the animals available to meet are specified in a simple and easy to read way using a small table.
![Animal meeting time table](/assets/images/animal-meeting-times.JPG)

- **ANIMAL PHOTOS**
  - The animal photos are featured on a seperate page which can be navigated to from the Animal Navigation Link on the top of the website.
  - The animal photos are featured together using masonry style, as each image may not be related to the other and therefore grouping them seperately would not be necessary.
  - The animal photos at first glance show the animals and what we do at the shelter and how we care for them.
![Animal photos](/assets/images/animal-photos.JPG)

- **CONTACT FORM**
  - The contact form is featured on a seperate page which can be navigated to from the Contact Navigation Link on the top the website.
  - The contact form has a background image of a dog holding a phone, which represents the purpose of that particular page.
  - The contact form has text input fields for first name, last name, email address, phone number, three radio buttons asking the reason: Adopt, Volunteer & Other Queries.
  - The submit button is featured with a value of Contact Me.
![Conatct form](/assets/images/contact-form.JPG)

- **FIND US AT**
  - The find us at section can be found right below the contact form, so users who might want to conctact or get to us right away can find us.
  - A google maps windows with the location is featured in the section, helping users find our location easily using this feature.
  - The address email address and phone number can be found right below the google maps window, making it easy for the users to find everything they need at first glance.
![Find us at](/assets/images/find-us-at.JPG)

- **FOOTER**
  - The footer can be found at the bottom of all pages. Making it easy for users at any point, be taken outside to the coressponding pages.
  - The social media pages are listed here using the icons to represent them.
  - Facebook, Instagram, Youtube and Twitter accounts can be neavigated to from the footer from any of the pages.
  - Clicking any of the links will open a seperate tab leaving the website open in the background for the users to easily return to, if they wish to do so.
![Footer](/assets/images/footer.JPG)

### FEATURES LEFT TO IMPLEMENT

- A seperate page showcasing videos, that can be controlled by the users, showcasing the infrastructure, activities and work carried out by the shelter.
- Article with audio elemnts which could help users get more information and updates on the shelter.
- Feedback section for users who have visited the shelter.

## TESTING

- This website has been tested to check if it works on different browsers such as Google Chrome, Microsoft Edge, Mozilla Firefox, Safari and Samsung internet.
- The website has been tested using the dev tools device toolbar on the browser to check if it functions and looks good on all standard screen sizes, showing it uses reponsive design.
- All text on the website has been checked to see if it is readable and is easy to understand.
- The contact form has been tested to make sure all fields apart from the optional radio buttons and textarea field are required to submit the form. And the submit button works.

## BUGS

### SOLVED BUGS

- The hero image disappeared after adding no-repeat center center after the url.
  - Fix: Changed the background-image property to background.
  
- The hero-outer properties were not getting applied.
  - Fix: Id of hero-outer had a space in the name instead of (-), so used the right format.

- The hero-image animation was not working.
  - Fix: Animation rules were placed outside the curly brackets. Moved the rules inside the brackets.
  
- Font-awesome icons were not appearing.
  - Fix: The initial font awesome code used was incorrect and had to be corrected and the icons started working.

- Cover text position was not relative to the image.
  - Fix: Add position of relative to the parent element, so child elements can set it's postion absolute to it.

## VALIDATOR TESTING

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

- CSS
  - No errors were found when passing through the official official [Jigsaw validator](https://jigsaw.w3.org/css-validator/)

- ACCESSIBILITY
  - The colours and fonts used are easy to read and checked using lighthouse in devtools.
![Accessibility score](/assets/images/score.JPG)

## DEPLOYMENT

- This site was deployed using GitHub pages. The steps used to deploy are:
  - In the GitHub repository go to the setting section.
  - Select the main branch as default branch
  - Go to the pages section and set branch to main and save.
  - Once done, the page provided link to the completed website.

The live link can be found here - [Peak District Animal Shelter](https://md-ash-dot.github.io/peak-district-animal-shelter/)

## CREDITS

### CONTENT

### MEDIA
