![Resilience Logo](https://github.com/ShaunWard/Milestone-Project-One/blob/master/images/Double%20Resilience.png?raw=true)
# RESILIENCE GYM WEBSITE
## Description
This is a fictional gym created for my first Milestone Project.

The purpose of this website is to attract and inform potential customers of the services on offer at Resilience Gym.

The website is split into 5 main pages:

- Home: An Introduction to the gym with a map of where the gym is.
- About Us: Background to the gym such as how long it has been around.
- What we Offer: Information on what we offer including classes, personal training and programmes.
- Contact Us: A form to contact the gym personel for queries about training sessions, classes, programmes etc as well as any general enquires.
- Sign Up: A Sign Up page to create an account and join the gym.

## Deployment
The Resilience Website has been deployed to [the authors github page](https://github.com/ShaunWard/Milestone-Project-One)

## Wireframes
Access wireframes from the links below

- [Home](https://wireframe.cc/8a3TTu)
- [Gallery](https://wireframe.cc/2hAhTz) - Became the About Us page
- [What we offer](https://wireframe.cc/CQMoWn)
- [Contact Us](https://wireframe.cc/ljCIyF) - Basic structure used for Contact Us and Sign Up Page

## User Experience (UX)

![Responsive Design Image](https://github.com/ShaunWard/Milestone-Project-One/blob/master/images/responsive-design-image.png?raw=true)

This site was created to present to potential customers what is available at Resilience Gym.

The colour scheme was used to clearly break up areas of the page from the navigation, to the page content and images, to the details in the footer. The colours chosen, such as red and black, were used to help create a powerful feeling within the viewer to make them feel empowered and want to make a change and get fit.

The page layout was designed to suit any screen size. The navigation bar will collapse into a drop down menu for smaller screens. Muliple images will arrange themselves from horizontal to vertical, as will the footer, all of which will help with a change in screen size.

Features such as the image carousel and flipboxes were used to make the page less static and to make the user feel more engaged in the experience of using the site. They also provide a useful way of presenting the images and information on classes and programmes.

![flipbox image](https://github.com/ShaunWard/Milestone-Project-One/blob/master/images/Flipbox-small.png?raw=true)

## User Stories

#### Potential Customer

- As a potential customer, I want to know about the background and history of the gym to understand where it has come from.
- As a potential customer, I want to see images of what the gym looks like before I decide to go.
- As a potential customer, I want to know what the gym has to offer to me, such as do they offer more than just gym access.
- As a potential customer, I want to know what the open hours of the gym are.
- As a potential customer, I want to know the location of the gym including an address and map.

Resilience achieves this by:

- Providing an About Us page to tell potential customers about the family owned gym and how they built it up from the beginning.
- Showing potential customers images of the gym throughout the site as well as clients workout out in the gym. The largest section of images being on the about us page.
- Providing a What We Offer Page specifically to inform customers of all the things available to them such as classes, personal training and workout programs.
- Showing the open hours clearly in the footer on every page and providing class times during the open hours on the What We Offer Page.
- Providing a large map in the Where To Find Us section of the Home page. Also included is a full address in the footer of every page.


#### Current Member

- As a member of the gym, I want to be able to easily book personal training sessions with my trainer.
- As a member of the gym, I want to be able to easily get another workout programme from the site to change up my training.
- As a member of the gym, I want to be able to quickly check class times

Resilience achieves this by:

- Allowing our staff to be easily contactable through the form on the Contact Us page, specifiying what information they require.
- Providing a selection of downloadable workout plans on the What We Offer Page under the workout plans section, and changes these workout plans periodically.
- Providing a list of classes with times on the What We Offer Page under the classes section.

## Features
There are various features on the site:

- Navigation bar - For ease of navigation around the site on any screen size. 
- Burger Icon - Smaller screen sizes use the 'burger' icon as a drop down for the navigation bar.
- Social Links - The footer contains social media links to allow easy access to the gyms social media sites to share stories and find more information.
- Flip boxes - Used on the What we offer page, this gives the page a clean look but also allows information relating to the subject to be contained behind the image.
- Forms - The Contact Page has a form to fill in to request more specific information around a query, containing radio buttons for choices of how to contact them. The Sign up page contains a form to allow the creation of a profile on the site.
- A Responsive design allows use on all sizes from desktops to phones.

### Features Left to Implement

- Adding a members area that allows you to view your membership, upcoming classes or programmes you have/have completed would be useful for current members.
- [Stripe](https://stripe.com/gb) connectivity would be put in place to take payments for memberships or individual class.

## Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

The various User Stories and Features of the website were tested manually as shown below.

1. Viewing background information and images of the gym:
    1. Go to the "About Us" page
    2. Scrolling up and down the page will give information around the history of the gym as well as images being available.
    
2. I want to know what the gym has to offer and download workout plans:
    On a desktop/laptop using the mouse:
    1. Go to the "What We Offer Page" page.
    2. Hover over over each image and view the box flipping round to reveal information about the subject/image.
    3. While hovering over the "Workout Plans" click on the links to download workout plans (nothing to download currently)
    
    On a mobile device such as a phone or tablet:
    1. Click on the burger icon in the top right of the screen.
    2. Go to the "What We Offer Page" page in the drop down.
    3. Click on each flip box to reveal information about the subject/image.
    4. Click on the links to download workout plans (nothing to download currently)
    
3. Finding out the opening hours or location of the gym:
    1. On the "Home" page scrolled down the page to find a map of the location of the gym.
    2. Scrolled further down to find the footer containing an address and opening hours of the gym.
    
4. Using the Contact Us Form:
    1. Go to the "Contact Us" page.
    2. Tried to submit the empty form and verified that an error "Please fill in this field" appears.
    3. Tried to submit the form with an invalid email address, error message asking for an email address with '@' symbol appears.
    4. Tried to submit the form with all inputs valid, verified in this scenario that the code institute success page appears.
    
5. Using the Sign Up Page:
    1. Go to the "Sign Up Now!" page.
    2. Tried to submit the empty form and verified that an error "Please fill in this field" appears.
    3. Tried to submit the form with an invalid email address, error message asking for an email address with '@' symbol appears.
    4. Tried to submit without a phone number, verified that an error "Please fill in this field" appears.
    5. Tried to submit without a password, verified that an error "Please fill in this field" appears.
    6. Tried to submit the form with all inputs valid, verified in this scenario that the code institute success page appears.

This site was tested using various resources such as:

- [Am I Responsive](http://ami.responsivedesign.is/) was used to test the site on various screen sizes to ensure the information could be viewed correctly
- [HTML Validator](https://validator.w3.org/) used to validate HTML
- [CSS Validator](https://jigsaw.w3.org/css-validator/) used to validate CSS
- [Pingdom](https://tools.pingdom.com/#5ca554057c800000) used to test speed of website and improve loading times

## Technologies

#### Languages Used
- HTML
- CSS

#### Frameworks Used
- Bootstrap

#### Tools Used
- [Am I Responsive](http://ami.responsivedesign.is/) for testing as above
- [wireframes.cc](https://wireframe.cc/): was used to create wireframes
- [fontawesome](https://fontawesome.com/icons?d=gallery): icons were used for social media links
- [Google Maps](https://www.google.com/maps): embedded into homepage to provide location.
- [Google Fonts](https://fonts.google.com/?selection.family=Lexend+Tera#standard-styles)
- [Gitpod](https://www.gitpod.io/): used to create the website.
- [JPEG mini](https://www.jpegmini.com/): was used to conpress images
- [Pingdom](https://tools.pingdom.com/#5ca554057c800000) used to test speed of website
- [Google](https://www.google.co.uk/) was used to find unlicenced images for use on the site

## Acknowledgements

I'd like to acknowledge my mentor, Felipe Souza Alarcon, for his support throughout this project.
