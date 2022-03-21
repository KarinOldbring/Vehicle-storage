# ** Oldbring Vehicle Storage**

Oldbring Vehicle Storage is a site designed to help people who are in need of storage for vehicles, whether it be vintage cars, boats or motorhomes. The site is targeted for people living in and around Linkoping, Sweden, who are looking for a safe and secure place for their leisure vehicles. 

## ** Planning Stage**

### **Targeted Audience**
* Users living nearby Linkoping who own leisure vehicles. 
* Users in need of flexible and large storage units. 

### **Site Aims**
* Create a site so that users can search online and find a place to store vehicles. 
* Show the user the benefits of using Oldbring Vehicle Storage. 
* Provide the user with price information and the location of the business. 
* Give the user an opportunity to get in touch or be contacted by Oldbring Vehicle Storage. 

### **Wireframes** 
To help organize the approach of this website I designed a basic wireframe to structure the layout for the different page areas. I consulted my father, who mainly runs the business, to make sure that the necessary information is included on the site. 
The different page areas consist of: 
* About
* Sign Up
* Contact

In general I stayed true to the initial design throughout the project.

### **Design choises**
* I chose a color scheme that I find clean and suits well with the hero image and more importantly easy to read for the user. I chose a very light grey (#e1e1e1) as background color for the entire page, to keep consistency. To ensure there is good contrast I set the text black (#000000). 
* As font I used Oswald for my headings and Roboto Condensed for the body text, ('https://fonts.googleapis.com/css2?family=Oswald:wght@300&family=Roboto+Condensed:wght@300&display=swap'). 

## **Features**
### **Nav-bar**

* The Nav-bar enables the user to easily navigate and find information required. It is located on the very top of the page. 
* For ease of navigation the different links of the nav-bar are underlined when hovered over. As the page size decreases the nav-bar is responsive and displays under the company name rather than horizontally along it. 
* Allows the user to skip to vital parts without having to scroll.

### **Hero-Image**
* The image represents one of the many types of vehicles that can be stored.
* The classic car is supposed to give the user a sense that Oldbring Vehicle Storage have a solid experience of handling precious vehicles. 
* The hero-image is supposed to work as an eye catcher when visiting the site. 
* The image doesn't have a key function for the site but is chosen from a design perspective. To make sure all users, including those using screen readers, have an equal experience when visiting the site an explanatory alt attribute was added. 

### **About**
* The About section will allow the user to see the advantages of storing their vehicle at Oldbring Vehicle Storage. 
* Here the user will find vital information regarding what we offer and also price proposals. As the page size decreases the text area make up more of the page and the image is being pushed below to improve user experience. 
* The information provided in this section gives the user vital information to determine whether they want to pursue collaboration. 

### **Sign Up
* A sign-up form allows the user to leave their contact information if they wish to be contacted. 
* The user will be asked to submit their contact information and then submit it. 
* A sign-up form is used to increase the customer base and gives the business owner a possibility to reach out to potential clients. 

### **Contact**
* The contact section gives the user the contact information for the business, and also the exact location. 
* If a user for some reason does not want to leave their contact information this section enabled the user to easily get in touch with Oldbring Vehicle Storage. Phone, email and Google Maps are displayed. 
* For this kind of business location is key and using Google Maps enables the user to get exat location of the business from their own location. 

### **Footer**
* Apart from the contact information the footer also contains links for various social media. 
* Social media are shown by using clickable links, making it easier for the user to visit. 
* Since many users today use social media as a way of retrieving information regarding a specific company this section helps them get there fast and easy. 

## **Future features to be added**
The Oldbring Vehicle Storage site is currently at the minimum viable product stage. Future features to be added to increase site usability include: 
* Virtual video tours of the facilities
* Online booking of storage space
* Online payment

## **Testing**
I have tested the site in Chrome, Edge and Firefox browsers, using Dev Tools to test responsiveness. I have also reviewed the site on both Android and IOS and experienced no issues. 

### **Responsiveness**
![AmIResponisive](https://user-images.githubusercontent.com/99074727/159252587-ecf75bfb-78dd-4215-b35e-ff834c8ed0b4.png)

http://ami.responsivedesign.is/?url=https%3A%2F%2Fkarinoldbring.github.io%2FVehicle-storage%2F
I have performed extensive testing to make sure that the site is fully responsive on small, medium and large siza screens. As well as testing in dev tools and using various mobile devices I also used "Am I Responsive" to ensure responsiveness. No website breaking issues were found. 
To make sure the site works well on all screen sizes I found three different key widths were necessary. 
1. **Laptops and desktops 1200px and below**
    * About section
        * Divs are displayed on top of each other rather than side by side. The size was also adjusted to better fit the screen size. 
2. **Smaller laptops and devices 900px and below**
    * Nav-bar
        * Smaller font-size for a better fit. The nav-bar list is to be displayed underneath company name, and in column on left hand side. 
    * Submit
        * The size of the forms submit button was changed to be clearly visible even on smaller devices. 
3. **Smaller devices 500px and below**
    * Hero-image
        * The text box in the hero image is removed and the actual text is instead placed underneath the hero image. The font-size is also reduced. 

### **Lighthouse**
![LighthouseMobile Project1](https://user-images.githubusercontent.com/99074727/159252744-2e19addf-19ba-4bc6-8fa2-1cd4a50a6bf7.png)
![LighthouseDesktop Projet1](https://user-images.githubusercontent.com/99074727/159252754-911c378b-d855-4867-a423-a94ea2e5d31d.png)

All sections have been tested with Lighthouse for both mobile and desktop versions. The score for desktop was between 99-100 and for mobile between 98-100. 
I found Lighthouse to be very helpful for identify poor practices such as using aria-labels on the input-fields in the form and title to the Google maps-link. 

### **Validators**
All HTML files were run through (https://validator.w3.org/) and my CSS file was run through (https://jigsaw.w3.org/css-validator/) to ensure all code meets the correct standard.

## **Bugs**
There are no known bugs on the site. 

## **Deployment**
I deployed the website on GitHub pages via the following:

1. From the projects repository go to the **settings** tab
1. On the left hand menu near the bottom click on the **pages** link
1. Under **Source** click on the button "None" which will produce a drop down
1. Click on **Main** and then click **Save**
1. The following message will appear:  **Your site is ready to be published**
1. After a few minutes the site will be published and the message will change to **Your site is published**

You can access the live site via the following link [Oldbring Vehicle Storage](https://karinoldbring.github.io/Vehicle-storage/)

## **Technology used**
Oldbring Vehicle Storage was built using HTML5 and CSS. 

## **Credits**

### **Content**
* [Oldbring Vehicle Storage](https://karinoldbring.github.io/Vehicle-storage/) all information on the website is in relation to Oldbring Vehicle Storage and was used with their permission. 
* The project was influenced by the Code Institutes code along project called Love running and the sample website in Portfolio 1. Whilst I have tried to deviate as much as possible and do my own thing, there may be some similarities in the code.
* For general research when tackling something I generally relied on the previous CI-course content and W3 Schools for information.
* Icons used are from [Font Awesome](https://fontawesome.com/) 
### **Media**
* The images used on the site were taken from [Pexels](https://www.pexels.com/)

### **Thanks**
* Many thanks to fellow students Matt Bodden_5P (regarding display/positioning) and Chris_Williams_5P (regarding media queries) for great support. Also many thanks to [Richard Wells](https://github.com/D0nni387) - Code Institute mentor, who has given me invaluable advice during this project! 
