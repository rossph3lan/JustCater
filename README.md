# JustCater

## Project Overview

Justcater is a catering service located in County Waterford. They cater for all events and functions. I made this website for the company so they can display menus, pictures and information about the company.

## User Stories

**As a developer**

- Create a project for my portfolio.

- Learn more about the technologies i have been studying and practising.

- For my client to be satisfied with my work and for it to drive more traffic to his business.

**As a business owner**

- Be able to see the large range of services we cater for.

- Be able to view photos of our past events and dishes.

- Be able to contact us for events they would like us to cater for.

- Browse our menus.

**As a customer**

- To Easily navigate thought the website.

- To read about this company and what they are about.

- To browse menus for my planned event.

- To view pictures of the food, they have to offer.

- To be able to contact JustCater for an inquiry.

- To see them on other social media platforms.

## Features

The main features of the site I wanted to focus on were the menus, gallery and the contact from.

- The menus can be found under the a paragraph. The images of the menus are clickable and open in another tab. I used the images instead of writing, so the user can see what the food looks like on the menus. Menus open in another page, so the user can easily navigate from where they left off.

- On the gallery page there is a short opening sentence followed by 24 images in a row of three. Images were picked to showcase the best of the company offerings. We wanted to show the quality of food, how we set up at functions and our team working at the functions.

- The form was another important feature for it allowed the user to communicate directly with the company. The paragraph about the form was designed to get the basic information from the customer that the company need to estimate the overall project.

## Structure

For the structure of the page, I wanted it simple and easy to navigate through for the user and from them to be able to get the information they were seeking.

- The navbar consists of the logo and a menu which offers three pages available on the website: Home, Gallery and Contact. The logo and be clicked to return to the home page.

- The home page consists of our main image to grab the users attention.

- Under the image is a paragraph describing the company.

- Under the paragraph we have our call to actions which is our menus with an image representing the described menu and a downloadable link to the menus which opens in a separate tab.

- At the end of our pages is the footer which is a black color with white font color. It has the company phone number, email address and social links. These are clickable links to bring the provided action.

- The gallery page consists of images of past events, dishes and members of the team at work.

- The contact page consists of a paragraph asking the user to give information that the company would need for an inquiry. It is followed by a form for the user to submit for any enquiry they would like to make to JustCater.

## Design : Fonts, Icons, Colors, Images

### Fonts

- The font I used for the headings is the "Merriweather" font which I found appealing on the eye and which had a professional appeal about it.

- The font I used for my paragraphs is the "Oswald" font which I have used before and have seen many times and is a font in which people are accustomed to seeing.

### Icons

- Icons were used for the social links as the icon is now more recognized than the brand name itself and users are used to seeing these icons and understand their meaning.

### Colors

- The primary color is white. I chose to use white as the background color and using black as the font color as I wanted the images displayed on the page to be popped out. I wanted the images to catch the users attention upon visiting the page. The colors of black and white also work very well together and can be understood easy.

### Images

- I used the JustCater logo image on my navbar. I wanted the logo to be seen on every page visited on the site.

- On the home page of the website, I have a responsive image it is a picture of beautiful canapes. I used this image because of the quality and canapes also have a wedding appeal and it would capture viewers attention and also other catering company in this area doesn't offer food of the kind.

- Below the main home images, I have three menus offering different choices based on occasion. Each of these menus has an image that is used to describe them. I used these images as my CTA's to get the user to want to see more of what these menus offered and consisted of.

- On the gallery page I used 24 images each in a row of three (Desktop view) as odd numbers are more catching to the eye. The images are sized large and I used a variety of different types of pictures to show off what JustCater can offer.

## Technologies Used

- The languages used in the project were HTML and CSS. Other frameworks were used such as:

- [Balsamiq Wireframes](https://balsamiq.com/) was used for my wireframes and sketches of my ideas.

- [Bootstrap](https://getbootstrap.com/) was used as my framework and helped me with the responsive views on devices and also with the structuring of my website.

- [Font Awesome](https://fontawesome.com/) was used for my social media links located on the footer.

## Testing

### Validation

- I tested the my code through [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to ensure my code was running smoothly with no errors.

### Testing Client User Stories

1. **As a customer of JustCater, I want to easily navigate thought the website.**

- The navigation of the website was structured for the user to easily find where they wanted to go and where the information the were seeking is.

- The menu consists of three pages: Home, Gallery and Contact. The most sought after pages of the user.

- The white color used in the background makes other contents of the page pop out, so the user is not distracted from the information.

2. **As a customer of JustCater, I want to read about this company and what they are about.**

- I have implemented paragraphs on the home page describing what the company does and what it has to offer the users.

3. **As a customer of JustCater, I want to browse menus for my planned event.**

- Menus are under paragraph about the business. There are three different samples.

- Menus are set to open in a different tab upon being clicked.

4. **As a customer of JustCater, I want to view pictures of the food they have to offer.**

- On arrival of the home page, a large grabbing image catches the users attention of beautiful canapes.

- There is a separate page for the gallery. On the gallery page it consists of 24 images. Images selected have been picked to show a variety of different aspects of the company, such as food, past events and the team at work.

- The clickable menus are also added by images which represent the type of menu they are looking at.

5. **As a customer of JustCater, I want to be able to contact JustCater for an inquiry.**

- The last page on the website is a contact page. I have made a form there for the user to contact the company regarding an inquiry.

- In the footer located on each page is a telephone number and email address of JustCater.

6. **As a customer of JustCater, I want to see them on other social media platforms.**

- Located in the footer element are social media links to other platforms that JustCater uses.

## Bugs

- Making my contact form i ran into a problem. Upon submiting the message a error 404 came up.

        <div class="container contact-form">
              <form method="post">
                 <div class="row">
                      <div class="col-md-6">
                          <div class="form-group">
                              <input type="text" name="txtName" class="form-control" placeholder="Your Name *" value="" />
                          </div>
                          <div class="form-group">
                              <input type="text" name="txtEmail" class="form-control" placeholder="Your Email *" value="" />
                          </div>
                          <div class="form-group">
                              <input type="text" name="txtPhone" class="form-control" placeholder="Your Phone Number *" value="" />
                          </div>
                          <div class="form-group">
                              <input type="submit" name="btnSubmit" class="btnContact" value="Send Message" />
                          </div>
                      </div>
                      <div class="col-md-6">
                          <div class="form-group">
                              <textarea name="txtMsg" class="form-control" placeholder="Your Message *" style="width: 100%; height: 150px;"></textarea>
                          </div>
                      </div>
                  </div>
              </form>

  </div>

- I decided to change my `form method` from `post` to `get`.

- I then added another page "thankyou.html" to show a thank you message for subbmision of the message which can redirect them back to the home page.

         <div class="container contact-form">
              <form method="get" action="thankyou.html">
                 <div class="row">
                      <div class="col-md-6">
                          <div class="form-group">
                              <input type="text" name="txtName" class="form-control" placeholder="Your Name *" value="" required>
                          </div>
                          <div class="form-group">
                              <input type="text" name="txtEmail" class="form-control" placeholder="Your Email *" value="" required>
                          </div>
                          <div class="form-group">
                              <input type="text" name="txtPhone" class="form-control" placeholder="Your Phone Number *" value="" required>
                          </div>
                          <div class="form-group">
                              <button type="submit" class="btn btn-dark">Submit</button>
                          </div>
                            </div>

                      <div class="col-md-6">
                          <div class="form-group">
                              <textarea name="txtMsg" class="form-control" placeholder="Your Message *" style="width: 100%; height: 150px;"></textarea>
                          </div>
                      </div>
                  </div>
              </form>

  </div>

## Deployment

This project was developed using [GitPod IDE](https://www.gitpod.io/), committed to git and pushed to GitHub using the built-in terminal with in GitPod.

To deploy this page to GitHub pages from its [GitHub repository](https://github.com/SmokeySam/just-cater), following steps were taken:

1. Log into to **GitHub**.

2. From the list of repositories on the left side, click **SmokeySam/just-cater**.

3. Select **Settings** from the menu item located near the top.

4. Scroll down to the **GitHub Pages** section.

5. Under **Source** click the menu labeled none and select **Master Branch**.

6. After selecting **Master Branch** the page is automatically refreshed, the website is now deployed.

7. Go back to the **GitHub Pages** section to retrieve the link to the deployed website.

### How to run this project locally

To clone this project from GitHub:

1.  Click this link to go to the [Project GitHub repository](https://github.com/SmokeySam/just-cater).

2.  Under the repository name click "Clone or Download."

3.  In the clone HTTPS section, copy the clone URL for the repository.

4.  In your local IDE open GitBash.

5.  Change the current working directory to the location where you want the cloned directory to be made.

6.  Type ` git clone`, then the URL you copied.

         `git clone https://github.com/SmokeySam/just-cater.git`

7.  Press Enter. Your local clone will be created.

## Running Locally

## Credits

- All code taken from other sources is documented below with links. Other code is wrote by myself with snippets or adjustments made upon reading and researching forums.
  Websites used to gain these pieces of information were [Youtube](https://www.youtube.com/), [Stack Overflow](https://stackoverflow.com/) and [W3Schools](https://www.w3schools.com/).

1. **Fonts**

- Fonts used were "Merriweather" and "Oswald". Both were imported from [Font Awesome](https://fontawesome.com/).

2. **Navbar**

- I styled my navbar by using documentation from the [Bootstrap](https://getbootstrap.com/docs/4.0/components/navbar/).

3. **Gallery**

- I structured the gallery page by using the Bootstrap image thumbnail and arranging it in rows and columns. [Bootstrap](https://getbootstrap.com/docs/4.4/content/images/).

4. **Contact Form**

- I got help with my contact form from [Bootsnip](https://bootsnipp.com/snippets/7nmOW) where I used certain pieces of the code used.

5. **Footer**

- My footer was taken from another project i had worked on during the course and small modifications were made to it. [Font Awesome](https://fontawesome.com/).

6. **README**

- The structure of my README file was taken from a series of videos offered by The Code Institute and also from [README Template](https://github.com/Code-Institute-Solutions/readme-template) page.

## Media

- Images used are owned by JustCater.

- Menus used are owned by JustCater.

## Acknowledgements

- I was inspiration to do this project because I have been part of JustCater from the start, and would like to see more customers engage with the company from an online point of view and for the company to grow. After learning these new skills, I was eager to develop this Website.
