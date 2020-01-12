# **the ginger trader**

# introduction

This project has been created so that the ginger trader handywoman business can boost sales of their services by 
highlighting the services offered and by showcasing previous projects alongside client testimonials. 

The site provides contact details and a form so customers can quickly and easily contact the business

# ux

-  **strategy** - the site is catchy, with a unique design and colour scheme for this sector.
It also is simple with minimal content, that acheives the site owner's and users' goals. It's easy to
contact the business owner to arrange a job
- **scope** - simple, functional features that meet the business objectives kept this development 
on schedule with potential future features listed below
- **structure** - the site has a consitent theme and style with a menu at the top right. Any clickable links 
have clear actions and responses. It's easy to know where you are on the site and the triangular
dividers reveal the content below the fold, and it's easy to get back to the top. 
- **skeleton** - information is revealed progressively as the user scrolls down the site and a limited number
of features gives good usability. 
- **surface** - the site is econimical in content, easily readable with a sensible sequence. 

## user stories

Site User wants to
- find a handyman/woman that will do a specific job for them

    - this is achieved by describing the handywoman business with the "who we are" feature at the top of the page
and listing the types of services avaiable with the "what we do" feature

- find a price for the job that they want to be done

    - this is achieved by incorporating an easy to use and submit form with the "get a quote" feature
     to get a quote along with direct contact details for the business

- see that the business has a solid background and reputation and works to a high standard
    
    - this is achieved by showing real projects carried out by the ginger trader and 
    associated customer testimonials about the work with the "testimonials" feature

Site Owner wants to
- grow their business and increase their client base by promoting their services

    - this is achieved with the simple, yet functional content and unique style of the site in the trader market,
    highlighting the independent nature of the business

- highlight the different services offered by the business

    - this is achieved with the "what we do" feature

- showcase their previous projects to demonstrate their quality of skills and customer satisfaction

    - this is achieved with the "testimonials" feature

- give the clients a quick and easy way for them to contact the business

    - this is achieved with the "get a quote" feature and contact details in the footer


# features

Features include:
- **who we are** - photo and info about the business to show the independent, 
personal side of the business and give a bit of background
- **what we do** icons and inforamtion showing the services offered so customers can 
quickly and easily see what is availbale
- **testimonials** - quotes and photos of previous customers with links to photos of 
the work carried out enabling new customers to see the quality of services
- **get a quote** - a simple form with placeholders to enable customers to quickly and easily 
contact the business about potential jobs

Future features:
- **meet the team** - a section to show futher detail about the business owner and any additional employees
- **chat bot** - for instant discussion about a potential/ongoing job (this would depend on 
additional staff being available to run it)
- **automatic reponse** - an email will be sent to the site owner on form submission (currently the form is just indicative). 
Plus, if a phone number is used in the get a quote form then an automated text maessage 
will be sent to the customer to acknowledge receipt of the request. 

# technologies used

- HTML: layout and content 
- CSS: styling
- Font Awesome: icons that visually represent the services the business offers https://fontawesome.com
- Google Fonts: a font family that represents the style and deign of the business https://fonts.google.com
- Bootstrap (CSS, JavaScript and JQuery) for the functionality of the sticky navbar, hamburger menu 
    and the grid structuring of the site https://bootstrapcdn.com

# testing

- links

All links have been checked - links to sections in the menu and links to local images. 
The links to external sites display a "coming soon" image as the social media for the business
has not yet been created. 

- get a quote form

On submission the form comes up with an error if it hasn't been filled in correctly (email address), 
or if required information (name, email address and details in the text box) is missing. The form doesn't yet submit information anywhere so there is no feedback 
for a response. 
In a future version the form data will be sent as an email to the site owner.  

- responsiveness

At every stage of the development process the responsiveness of the site has been checked (within gitpod and google inspect) as 
the grid structuring uses responsive parameters for display effectiveness i.e. the "what we do" and "testimonials" sections
are displayed as a single column on mobile and as two columns for a medium screen width and four columns for a large screen width.
The site has also been tested on different browsers e.g. Chrome, Firefox, IE.  

# deployment

The site has been deployed on the developer's GitHub site through GitHub Pages.

Files added to the GitHub repository (git add)

Files then commited to the respository (git commit)

Files then pushed to GitHub (git push)

The site can be accessed at https://github.com/junokili/the-ginger-trader

# credits

- **content:** text and code is the developer's own apart from the additional code snippets used below 
(and commented on in style.css):

    - CSS gradients (w3schools)
https://www.w3schools.com/css/css3_gradients.asp

    - Hamburger outline removal (stackoverflow):
https://stackoverflow.com/questions/50668594/removing-the-border-color-of-the-navbar-toggler-hamburger-icon-bootstrap-4/50668740

    - Adding alt text to an image styled in the css file (stackoverflow):
https://stackoverflow.com/questions/4216035/css-background-image-alt-attribute

    - CSS box shadow (CSSmatic):
https://www.cssmatic.com/box-shadow

    - Divider triangle (Aries Dagraca)
https://iheartpagelines.com/creating-the-big-triangle-separator/


- **media:** the photos used in this site are attributed to: 
    - the ginger trader: the-ginger-trader.jpg, diy-jobs-the-ginger-trader.png, wallpapering-the-ginger-trader.jpg) 
    - the developer: testimonial-1.jpg, testimonial-2.jpg
    - VectorStock: coming-soon.jpg https://www.vectorstock.com/royalty-free-vector/coming-soon-neon-sign-coming-soon-badge-in-vector-21133321
    - seeklogo: city-guilds-logo.png https://seeklogo.com/vector-logo/213843/city-guilds

- **acknowledgments:** the inspiration for this project has come from a shared career change path between the ginger trainer and the
developer, with design inspiration that came from the ginger trader's kitchen and the pantone colour palettes
