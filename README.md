# Blister Sisters

## Fully functioning static HTML/CSS/Bootsrap website.

Blister Sisters is a website created to celebrate a community of women who come together to explore the outdoors, share stories, and support each other through the joys and challenges of hiking. By providing a space for women to connect, learn, and inspire one another, Blister Sisters highlights the significant connection between walking, friendship, and mental well-being.

To view the deployed website click [here](https://jolantadjatlova.github.io/blister-sisters/).

![screenshot](doc/blister-sisters-responsive-display.png) 

# UX


## Website Intentions

**For the User:**
- Discover the Blister Sisters community and how they support women hikers.
- Read inspiring stories about women who use hiking to improve their mental well-being.
- Find upcoming meet-ups or ways to join group hikes.
- Share their own hiking experiences or sign up for events.

**For the Site Developer:**
- Provide clear, welcoming content that resonates with women looking for community support.
- Ensure the site is intuitive to navigate, with simple CTAs for joining or sharing stories.
- Create a warm, rustic aesthetic that reflects nature and togetherness.

## User Goals
- Easy-to-use navigation
- Clear CTAs for joining hikes
- Warm, welcoming design
- Accessible on mobile, tablet, and desktop
- Simple way to sign up

## User Stories
- As a user, I need easy navigation and a user-friendly design, including a
 responsive layout for my device, so I can find hiking information quickly and efficiently without
 frustration.
 - As a user,  I want to see high quality images and engaging descriptions of hiking
 trails and scenery, so I can decide if it's the right place for me to explore.
 - As a user,  I need to find hiking locations, contact details for inquiries, so I can plan my hike confidently.
 - As a user, I want to sign up for my chosen hike/s through a simple form.
 - As a user, I want clear and helpful information about what to pack for a hike, so I feel safe and prepared on the day.
 - As a user, I want to compare hike prices and available bundle deals, so I can choose an option that fits my budget.

## Creation Process using the Agile Software Development Method

### Requirements
It is a B2C website aimed at women looking to join a supportive hiking community.  
The site should deliver motivating content, clear information on meet-ups, and encourage visitors to get involved by sharing their stories or contacting organizers.

### Scope
The website will feature:
- A minimalist, nature-inspired design using earthy colors and friendly typography.
- Core pages: a landing page, a ‘Meet the Sisters’ section with stories, and a contact form.
- An emphasis on mental health benefits tied to hiking and community.
- Consistent visual language across images, colors, and text to maintain trust and alignment.

## Architecture & Design
**Landing Page:**  
- A hero image that reflects the outdoors and community spirit.
- Immediate CTA to “Join a Hike”.

**Meet the Sisters:**  
- A page highlighting personal stories, possibly with short bios or quotes.
- Inspiring images of women hiking together.

**Contact Form:**  
- Easy-to-use form for users to sign up for hikes.

---
## Wireframes

Wireframes were designed using Balsamiq tool. Following best practices, mobile version was designed first, then tablet and lastly the laptop view.

### Home Page
![Home Page](doc/home.png)

### About Us Page
![About Us](doc/about-us.png)

### Hikes Page
![Hikes](doc/hikes.png)

### Prices and Packages Page
![Prices and Packages](doc/prices-and-packages.png)

### Checklist Page
![Checklist](doc/check-list.png)

### Thank You Page
![Thank You](doc/thank-you.png)

## Design Choices

### Typography
The primary font used for this website is [Lato](https://fonts.google.com/specimen/Lato?query=lato "Lato"), a clean and modern sans-serif typeface chosen for its readability and friendly appearance. It is used across all body text to ensure a comfortable reading experience on both desktop and mobile devices.

The heading font is [EB Garamond](https://fonts.google.com/specimen/EB+Garamond "EB Garamond"), a classic serif typeface that adds elegance and warmth. Its use in section headings and titles creates a sense of contrast and visual hierarchy, pairing well with the simplicity of Lato.

### Colour Scheme
The color scheme was generated using Coolors.co, inspired by the website’s hero image of a mountain at sunrise. The palette reflects natural tones of morning light and earthy environment, creating a calm and welcoming atmosphere.

![Color Palette](doc/palette.png) 

### Contrast Grid
Using Contrast Grid helped identify which colour pairings work best for the website in terms of readability and visual appeal, as well as which ones to avoid to maintain accessibility standards.

![Contrast Grid](doc/contrast-grid.png)

| CSS Name             | HEX                       | Usage                                                                |
|----------------------|---------------------------|----------------------------------------------------------------------|
| `--color-dark-green` | `#1C2B28`                 | Body text, headings, hike descriptions, footer text                  |
| `--color-warm-pink`  | `#B6655D`                 | Button backgrounds, hover buttons, call-to-action highlights         |
| `--color-soft-beige` | `#FDF6E3`                 | Background for body, sections                                        |
| `--text-light`       | `#ffffff`                 | Hero text, header text, footer text, buttons                         |
| `--color-light-grey` | `#f8f9fa`                 | Navbar background, checklist card borders                            |
                                      
### Images
As this hiking club is a fictional project, all images were generated using ChatGPT. The goal was to capture the look and feel of real hiking experiences in the UK, with a natural, welcoming tone. Image sizes were optimised using Pixlr to improve performance across devices.

### Responsiveness 
My website is responsive across different screen sizes, using a combination of Bootstrap’s responsive grid system and custom CSS media queries. This ensures that content adjusts well on desktop, tablet, and mobile, maintaining a consistent and user-friendly experience.

| Breakpoint Range         | Usage                                                                 |
|--------------------------|------------------------------------------------------------------------|
| `<400px`                 | Adjusts scroll padding and layout tweaks for very small screens        |
| `401px – 768px`          | Adjusts scroll padding for small tablets                               |
| `769px – 1024px`         | Applies specific styles for medium-sized devices like tablets          |
| `>1024px` (default)      | Displays the full desktop layout                                       |

# Features
This website offers a clean and friendly layout that's easy to navigate, whether you're visiting from a phone, tablet, or desktop. Visitors can explore key sections like hikes, pricing, and a checklist, all styled with consistent colors and typography that reflect the brand. Each hike includes clear descriptions, images, and a sign-up button to make booking easy. There's also an embedded Google Map to help users find meeting points, and a detailed checklist section to help hikers feel prepared. The design aims to be both welcoming and informative — highlighting connection, nature, and support.

## Existing Features

| Feature | Notes | Screenshot |
| --- | --- | --- |
| Navbar | The navbar is simple, fixed to the top of the page, and includes a custom mountain icon as a logo to reflect the hiking theme. It’s fully responsive using Bootstrap's navbar classes — on smaller screens, the links collapse into a mobile-friendly toggle menu. Navigation is smooth and intuitive, with anchor links that scroll directly to each section of the page like About Us, Hikes, and Pricing.|![Navbar](doc/navbar-image.png) 
| Hero Section | The homepage opens with a strong introduction that highlights the mission of Blister Sisters and sets a calming, empowering tone. With a scenic mountain background and a central message, it invites visitors to explore the community and understand the supportive nature of the hikes. |![hero](doc/hero-section.png)|
| About Us page | The About Us section introduces the Blister Sisters mission, highlighting the founders’ passion for hiking and women’s wellbeing. It emphasizes the group’s focus on community, conversation, and support through guided hikes in iconic UK landscapes.| ![about us](doc/about-us-page.png)
| Hikes page| The Hikes page showcases the guided trails offered by Blister Sisters, including Scafell Pike, Snowdon, and Ben Nevis. Each hike section includes a scenic image, detailed description, and a 'Sign Up' button. The layout alternates text and images for visual balance, making it easy for users to explore options and choose their adventure.|![hikes](doc/hikes-page.png)
| Sign Up form |The Sign Up Form appears as a modal when users click the “Sign Up” button for any hike. It collects key details—name, email address, phone number, and selected hike—allowing users to register quickly and easily. The form is styled consistently with the site’s color palette and includes basic input validation. Upon submission, users are redirected to a confirmation page.|![signup](doc/sign-up-page.png)|
| Success Page |The Success Page provides users with a friendly confirmation message after submitting the sign-up form. Featuring a bold “Thank You!” header in the brand’s color scheme and a styled ‘Back to Home’ button, the page reassures users that their submission was successful and guides them smoothly back to the homepage.|![success](doc/success-page.png)|
| Checklist Page | The Checklist page provides a clear, categorized list of essential items for a safe and comfortable hike. It’s divided into Essentials, Weather Dependent, Recommended Clothing, and Optional Extras — helping hikers prepare confidently for all conditions.|![checklist](doc/checklist-page.png)|
| Meeting Points Page | The Meeting Points page provides hikers with exact meetup locations and times for each trail, complete with embedded Google Maps for easy navigation and planning.|![meetingpoints](doc/meeting-points-page.png)|
| Pricing Page | The Pricing page outlines individual hike costs along with a discounted bundle offer for all three hikes. It helps users compare value and choose based on their experience and preferences.|![pricing](doc/pricing-page.png)|
| 404 Page | A dedicated 404 page is designed to assist users who reach a missing or incorrect URL. Consistent with the site’s overall style, it supports easy navigation back to the homepage and reinforces a polished user experience.|![404html](doc/404.html-page.png) |
| Footer | The footer includes contact information, social media icons for Instagram, Facebook, and Twitter, and a copyright notice. It provides users with a clear way to connect and reinforces brand presence across all pages. | ![footer](doc/footer-page.png) |

### Future Features
- **Expanded Hike Listings**: Expand available trails and introduce filter options based on location, duration, or difficulty to accommodate different user preferences.
- **Booking & Payment System**: Integrate online booking and secure payment functionality so users can reserve and pay for guided hikes directly through the site.

# Tools / Technologies

| Tools / Tech                                                     | Purpose                                                |
|------------------------------------------------------------------|--------------------------------------------------------|
|[Git](https://git-scm.com/)                                       | Track changes and manage code history.                 |
|[GitHub](https://github.com)                                      | Store and share the repository.                        |
|[VS Code](https://code.visualstudio.com)                          | Writing and organizing all project files.              |
|[HTML](https://en.wikipedia.org/wiki/HTML)                        | Building the basic structure of website.               |
|[CSS](https://en.wikipedia.org/wiki/CSS)                          | Designing layout and visual elements.                  |
|[Bootstrap](https://getbootstrap.com)                             | Used for responsive layout and reusable UI components. |
|[Balsamiq](https://balsamiq.com/wireframes)                       | Create wireframes.                                     |
|[Coolors](https://coolors.co/)                                    | Generating the project’s colour palette.               |
|[Eight Shapes](https://contrast-grid.eightshapes.com/)            | Generating contrast grid.                              |
|[Pixlr](https://pixlr.com/)                                       | Resizing and converting images.                        |
|[Font Awesome](https://fontawesome.com)                           | Adding social icons and other visual elements.         |
|[ChatGPT](https://chat.openai.com)                                | Assisted in writing content and generated all images.  |
|[W3Schools](https://www.w3schools.com)                            | Reference for HTML, CSS, and Bootstrap syntax and tips.|
|[W3C HTML Validation Service](https://validator.w3.org/)          | Check HTML for syntax error.                           |
|[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)| Check CSS for syntax error.                            |
|[Stack Overflow](https://stackoverflow.com)                       | Resource for debugging and resolving technical issues. |

# Testing
## Bugs

## Responsiveness Test

## Code Validation

### HTML

### CSS

## User Story Testing
| User Story                                    |Result | Pass | Evidence |
|-----------------------------------------------|------------------------------------------------------|------|----------|
| As a user, I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find hiking information quickly and efficiently without frustration. | The navbar provides clear links to each section, and the responsive layout ensures usability on all screen sizes. | P |                     |
| As a user, I want to see high quality images and engaging descriptions of hiking trails and scenery, so I can decide if it's the right place for me to explore. | Each hike section includes a high-quality image and a detailed, inviting description of the trail. | P | |
| As a user, I need to find hiking locations and contact details for inquiries, so I can plan my hike confidently. | The Hikes section provides detailed location info, and contact details are available in the footer and Contact page. | P | |
| As a user, I want clear and helpful information about what to pack for a hike, so I feel safe and prepared on the day. | The Checklist section provides categorized packing lists covering essentials, clothing, weather-dependent gear, and optional extras. | P | |
| As a user, I want to sign up for my chosen hike/s through a simple form. | A modal sign-up form allows users to register for individual hikes or the bundle, with fields for name, email, phone, and hike selection. | P | |
| As a user, I want to compare hike prices and available bundle deals, so I can choose an option that fits my budget. | The Pricing section includes a detailed table showing individual hike costs and a clearly marked discounted bundle offer. | P | |

# Deployment

## To deploy the project

Blister Sisters was deployed early in the process to GitHub pages via the following steps:

- Navigate to the repository on GitHub and click on **Settings**.

- In the side navigation and select **Pages**.

- In the **None** dropdown and choose **Main**.

- Click on the **Save** button.

- The website is now live at https://jolantadjatlova.github.io/blister-sisters/.

_Any changes required to the website, they can be made, committed and pushed to GitHub._

## To fork the project

Forking the GitHub repository allows you to create a duplicate of a local repository. This is done so that modifications to the copy can be performed without compromising the original repository.

- Log in to GitHub.
- Locate the repository.
- Click to open it.
- The fork button is located on the right side of the repository menu.
- To copy the repository to your GitHub account, click the button.

## To clone the project

- Log in to GitHub.
- Navigate to the main page of the repository and click Code.
- Copy the URL for the repository.
- Open your local IDE.
- Change the current working directory to the location where you want the cloned directory.
- Type git clone, and then paste the URL you copied earlier.
- Press Enter to create your local clone.

# Credits

#### Feedback, advice and support:

  - [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin")

#### Learning help and Resources

- [Code Institute](https://codeinstitute.net/ "Code Institute")
- [W3 Schools](https://www.w3schools.com/ "W3 Schools")
- [Slack](https://slack.com/intl/en-gb/ "Slack")
- [Stack Overflow](https://stackoverflow.com/ "Stack Overflow")

#### Images:

- [ChatGPT](https://chatgpt.com/ "ChatGPT")
- [Favicon.io](https://favicon.io "Favicon.io")
- [Pixlr](https://pixlr.com/ "Pixlr")


#### Visual Content:

- [Contrast Grid](https://contrast-grid.eightshapes.com/?version=1.1.0&background-colors=&foreground-colors=%23C0C0C0%0D%0A%2373937E%0D%0A%23053501%0D%0A%23000000%0D%0A%23FFFFFF&es-color-form__tile-size=compact&es-color-form__show-contrast=aaa&es-color-form__show-contrast=aa&es-color-form__show-contrast=aa18&es-color-form__show-contrast=dnp "Contrast Grid")
- [Balsamiq](https://balsamiq.com/education/ "Balsamiq")
- [Font Awesome](https://fontawesome.com/search?q=menu&o=r&ic=free "Font Awesome")
- [Coolors](http://https://coolors.co/ "Coolors")









