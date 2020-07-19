# Tia112-Milestone-Project-1---Master
Milestone Project 1
**Milestone project 1**

I began my project initially with an idea to do build a website for a local
boxing club but then realised that I much needed a website showcasing my
portfolio which I would have to do at some point anyway.

The structure I followed to design the site was the 5 planes of UX:

**Strategy**

The portfolio would be designed to attract potential employers and recruiters.
The site focuses on a number of technologies used which are demonstrated within
the site and as mock-up projects.

After some research I found that recruiters are keen to learn about the skills
and experience that potential employees possess and they expect to see this
clearly on their sites as well as any projects they have been on. Therefore the
site needs to be easy to navigate and the information presented needs to be
clear. Recruiters also look at hundreds of sites in a day so the site needs to
be easy to navigate and attractive for the site to stand out.

The technologies and skills information are showcased to keep recruiters and
employers interested enough to stay on the site and eventually the main goal
would be for them to use the “Contact me” form and links.

**Scope**

Defines the functional and content requirements. What are the features, and
content contained in the application or product. The requirements should fulfil
and be aligned with the strategic goals.

Functional Requirements It’s the requirements about the functions, or features
in the product, how features work with each other, and how they interrelate with
each other. These features are what user need to reach the objectives.

The site starts with a main page, then branches off into three different
sections as required. My main page would have a summary of my skills in the form
of icons but would be more detailed on the skills page.

As mentioned, the main goal is for recruiters/potential customers use the links
or a contact form. This will highlighted on every page so there are options
available for contact.

**Structure**

Features and Functionality

Main page – Home page

The home page goal is to give a look which is pleasing to the eye and to inform
potential employers and recruiters a little bit about myself and my skillset.

\- easily contact me for work through Linkedin, Twitter and a contact form.

\- access my skills page and other pages

The links are displayed in the header and footer for them to access -
ultimately, accessibility of the site underpins the simple and effective design.

The home page features an image in centre of the page with a navigation bar and
footer.

The navigation bar has links for ease of usability to encourage users to stay on
the site. I wanted to highlight my skills on the main page as well as the other
pages. The lightbulb icon was used as a feature to click on and read more about
my skills on the skills page as well as having the option to navigate to it from
the navigation bar.

At the bottom of my page I have a contact me button which the user can click on
and it directs them to the contacts page which is also displayed in the
navigation bar.

The different ways to access the different pages and links were intentionally
included as a feature for efficiency so the user does not get tired looking for
links.

All of the pages are made responsive. The main image representing myself in a
work environment stays the same in mobile view (reduced size), however changes
shape in the 5k+ view. This decision was made to ensure a greater proportion of
the screen was used so that not everything looked centralised.

The responsive design on my site was included to cater for the various mobile,
tablet and corporate displays. This would ensure that the site wouldn’t be
degraded and remain clean regardless of which device it was viewed on.

All of my links are highlighted when hovering over for users to be aware of the
different accessibility to my other pages, Instagram, LinkedIn and Twitter which
are all forms of contact.

**Skills Page**

The skills page have the same icons representing my skills as on the main page.
The icons have been made larger on this page to show that the focus is on the
skills. A summary of the skills are next to the icon making it clear for the
user to read. A concise description was written so that the user is not
inundated by too much information to read on the page keeping it simple and
clean.

The footer includes icons of the different links for contact again trying to
meet the objective which is for the user to contact me.

The navigation bar is on every page with the link to my next page which is the
projects page for easy accessibility.

**Projects Page**

This page showcases the conceptual projects with a description of the
technologies and how they were used on each project. A link is provided so the
users can go to the actual page where the project site is running for a fuller
experience. This link is under each project again attracting the user to stay on
the site and learn more about my work through easy navigation.

The size of the pictures had to be modified for responsiveness.

**Contacts page**

The user has two ways to navigate to this page from the contact me button on the
home page and through the navigation bar on every page.

The form has sections for personal contact details and any message they want to
leave me. It is a simple form so that users do not find it tedious to fill out.
The main feature of this form is user input validation. For example the user
would not be able to submit the form unless the email contains the correct email
format. This has been implemented using simple html/bootstrap features.

**Skeleton**

I have included the wireframes of how I wanted the site to flow and look
visually – in mobile, desktop and larger displays (5k+). It also helped me in
presenting and organising information in the correct manner.

Wireframes are located here:

<https://github.com/Tia112/Tia112-Milestone-Project-1---Master/tree/master/wireframes>

**Surface**

I wanted a simple, fresh but fun design. The colour I chose was a light grey
with a hint of lilac which paired well with my slightly funny caricature image
representing me. The background colour on each page was broken up with white
blocks to make it visually impacting. The lightbulb image was used because it
was the first idea (i.e. lightbulb moment) which I thought might add some
personality to the site in a subtle way. It was used again as a link to my
skills page to make it fun for the user.

The use of a Dancing script gave the site a quirky but modern look. Typography
was consistent across the site to provide a uniform and clean impression.

The use of *rems* was used instead of pixels (px) to allow for easier
scalability and, to accommodate for everyone including the visually impaired.

The clean look makes it easier for users to navigate and pay attention to the
information on the screen rather than be bedazzled by too many images.

**Technologies Used**

\- HTML

\- CSS

\- (Bootstrap)

**Testing**

Initially, the code was produced and tested in Cloud9 however due to issues with
the environment and security, I moved to a localised environment and pushed code
to GitHub in this manner. When testing the site I focused primarily on
navigation and function BEFORE, looking at the cosmetics.

| **Test Description**                                              | **Expected Outcome**                                                                                                        | **Actual Outcome**                                                                                                          | **Re-Test**   |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|---------------|
| Projects page – Navbar                                            | Customised Navbar with lightbulb image loads on the left Links navigate to other pages                                      | Passed                                                                                                                      | N/A           |
| Social Media Links                                                | Testing links to open up in a different browser                                                                             | Fail Added \<a .. target="_blank"\>                                                                                         | Passed        |
| Hover states                                                      | Hover states colour vibrant enough to users                                                                                 | Fail Change to a bright colour                                                                                              | Passed        |
| Central image                                                     | Image stretches across page without distortion                                                                              | Fail Extended the image by adding on images -shapes                                                                         | Passed        |
| Contact Me button                                                 | Navigates to contact page                                                                                                   | Passed                                                                                                                      | N/A           |
| Responsiveness in mobile view                                     | Images and content in mobile view load without problems                                                                     | Failed The sizing of images and fonts needed to be changed                                                                  | Pass          |
| Responsiveness in 5k view                                         | Central image and content load in 5k without problem                                                                        | Failed The shape of image had to be changed to reduce large empty spaces Font sizing was changed                            | Pass          |
| Skills Page- Responsiveness mobile view Responsiveness in 5K view | Images and content load nicely in mobile view Images and font load properly in 5K view                                      | Failed Failed Formatting was not in order- adjustments made in css Both images and fonts had to be increased in size in css | Passed Passed |
| Projects page- links                                              | Links opening up to the live projects pages                                                                                 | Passed                                                                                                                      | Failed        |
| Responsiveness in mobile view                                     | Page loads nicely, images and content                                                                                       | Passed                                                                                                                      | N/A           |
| Responsiveness in 5K                                              | Page loads in proportion                                                                                                    | Failed Images and fonts made larger                                                                                         | Passed        |
| Contacts Page – Form validation                                   | Form validation to check format of email address Text entered into the fields pre-submission All fields had to be populated | Failed Allowing users to bypass validation- amended code by getting the appropriate bootstrap code for form control         | Passed        |
| Responsiveness in mobile view                                     | Contact form                                                                                                                | Failed Form too small Text are too small- changed code in css                                                               | Passed        |
| Responsiveness in 5K                                              | Contact form                                                                                                                | Failed Form was too small- amended in css                                                                                   | Passed        |
| Browser compatibility for the whole site                          | Tested site using different brewers Firefox, Safari, Chrome, IE and Edge.                                                   | Passed                                                                                                                      | N/A           |
| Orientation in mobile view                                        | Tested site in landscape And portrait orientation                                                                           | Passed                                                                                                                      | N/A           |

**Code Validation**

CSS was validated using the W3C CSS Validation Service
(<https://jigsaw.w3.org/css-validator/>)

HTML was validated using the W3C Markup Validation Service
(<https://validator.w3.org/>)

**Deployment**

The site is hosted using GitHub Pages, and is available publicly on GitHub. In
order to deploy the site, I initially created an account in GitHub (Tia112) and
a repository
([Tia112-Milestone-Project-1](https://github.com/Tia112/Tia112-Milestone-Project-1---Master))
which I linked within my local PC development environment.

Initially, after falling off of Cloud9, I moved to using Atom as my IDE which
was great, however, I felt the integration between Atom and GitHub was a little
temperamental. Thereon, I used GitHub Desktop to commit my changes locally and
push them out to my GithHub repo.

As I progressed, I became more comfortable in with this process and on my way,
moved on from Atom to start using Visual Studio Code. This has now become the
defacto standard and my tool of trade!

I used GitHub Pages functionality to host my site early on in the project, where
it now resides in its entirety -
<https://tia112.github.io/Tia112-Milestone-Project-1---Master/>. The ability to
deploy the site using GitHub gave the opportunity for not only me, but for
others to test the site, and give some realistic unbiased feedback for me to
on-board.

**Conclusion**

In the future I would add my own projects to the project page. I would also have
proper validation for my contact form and to be able to send acknowledgements
for contact form submissions.

**References**

The following section includes references to elements used within my site – this
includes images, icons, code etc…

**Images**

Favicon Generator ([www.favicon.cc](http://www.favicon.cc))

VectorStock Images (vectorstock.com)

FreePik.com

Fiverr.com

Flaticon.com

Fontawesome.com

W3.org

Envoy.com

Omnitech-inc.com

Lovecarreviews.com

**Code**

Getbootstrap.com (used and amended as a guide for navbar/collapse+branding,
contact form, modal and buttons).

**Content**

The content on the projects page were for educational purposes only and the
projects were not designed by me.

Links to project were provided by SteelKiwi.com.

All the information on the site is written by myself.

#### **Acknowledgements**

A heartfelt Thankyou to my mentor Brian Macharia for all his time and efforts to
guide me through this project.

A special Thankyou to Lucy Rush, (Studentcare) \@ CodeInstitute who has been an
understanding ear in my time of crisis.

**Disclaimer**

This site and it’s contents were for educational purposes only.
