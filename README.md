# Reading Abbey Quarter

The aim of this website is to provide information for people who are visiting Reading Abbey Quarter, an area filled with historical interest in the heart of Reading, UK. The site intends to target both people who are specifically interested in aspects of the history of Reading and casual visitors who may be curious about something they may come across. It will provide photographic and textual information so people can match objects and locations with historical events. 

According to [Historic England](https://historicengland.org.uk/research/heritage-counts/heritage-and-economy/visitor-economy/), 3 in 5 adults (63%) visited a heritage site in person in the last 12 months (DCMS, 2023). The most popular heritage visitor sites include visits to parks/gardens with historic features (40%), followed by towns and cities with celebrated histories (39%) (DCMS, 2023). I therefore believe there will be widespread interest in a site of this nature.

## Features
### Navigation bar
The navigation bar will provide an intuitive way of navigating the site with a consistent appearance across all pages. It is reactive to different screen sizes, with a dropdown on mobile screens and a bar on screens of 768px or higher. 

### Footer. 
The footer provides links to external sites which will help a user plan their trip. These are the local museum, the local bus company and Tripadvisor. These open in external tabs so users won't be taken away from the page.
The appearance of the header and footer will help  tie the site together across the pages. 

### The Timeline
The landing page provides a timeline of the most pertinent events. the aim of this site will be to help users contextualise the objects and locations the see with wider historical events they may already know about (such as the dissolution of the monasteries).

![Screenshot of the timeline page](assets/images/timelinepage.jpg)

### The Gallery
The gallery will have images of the most prominent locations and objects in the abbey quarter with short explanations of what they are. This will help users understand what the things they see during a visit are.

![Screenshot of the gallery page](assets/images/gallerypage.jpg)

### Tour signup form.
The final page is a form allowing users to signup to a guided tour. The form takes inputs for first and last name and email address. These are mandatory and placeholder text is provided to guide the user. There is also a drop down menu for party size and a calendar with radio buttons to book a day and time. This is currently linked to a 404 page not found. 

![Screenshot of tour signup page](assets/images/tourpage.jpg)

## Testing

The site was tested in Chrome and Firefox. Developer tools was used, particularly with Galaxy Z fold 5, Iphone SE and IPad Mini, as well as the responsiveness feature. The full size version was tested on 11 and 22 inch screens. 
 
I have asked three friends for their feedback on the overall design and usability.

### HTML
An unclosed tag was found in testing through the official W3C validator and corrected. All pages were found to be bug free.

#### Timeline validation
 ![Screenshot of index.html validation](assets/images/index.htmlw3validator.png)

#### Gallery page validation
![Screenshot of gallery.html validation](assets/images/gallery.htmlw3validator.png)

#### Tour signup validation
![Screenshot of index.html validation](assets/images/toursignup.htmlw3validator.png)

### CSS
No errors were found when passing through the official (Jigsaw) validator
![Screenshot of css validation](assets/images/cssw3cvalidation.png)

One warning was given, as the validator doesn;t check imported stylings of gooogle fonts:
![Screenshot of css validation warning](assets/images/cssw3cvalidationwarning.png)

### Lighthouse
The site was tested in lighthouse. The site performed poorly in the performance category due to the size of the images used. I compressed and reuploaded these and while this did increase load times it is still slower than I would like. The original images were taken by myself and were I to revisit the site I would like to use smaller images to increase user experience.  The report also reccomended resizing some <h2> and <h3> elements and the addition of some aria lables. This has been done and the scores have improved as can be seen below.

#### Timeline page
![screenshot of lighthouse report](assets/images/index.htmllighthouse.png)

#### Gallery page
![screenshot of lighthouse report](assets/images/gallerylighthouse.png)

#### Tour signup page
![screenshot of lighthouse report](assets/images/tourlighthouse.png)

## Deployment

The application was created on Gitpod using The Code Institute template (https://github.com/Code-Institute-Org/gitpod-full-template) and VS Code Plugin and deployed to Github with the following steps:

1. Login to Github, otherwise create an account.
2. Navigate to the repository ('Explore -> 'ewradcliffe/Reading-Abbey-Quarter') or follow the link (https://github.com/ewradcliffe/Reading-Abbey-Quarter).
3. Once in the repository navigate to the 'Settings' tab.
4. Navigate to the 'Pages' section, select the branch to deploy and save the changes.

The link to website is https://ewradcliffe.github.io/Reading-Abbey-Quarter/

## Credits

The  code for the header and Footer were taken from the code institute [Love Running Project](https://codeinstitute.net).

The Timeline was taken from [W3 Schools Timeline lesson](https://www.w3schools.com/howto/howto_css_timeline.asp)

Kevin Powell [box-shadow vs filter: drop-shadow()](https://www.youtube.com/watch?v=8Z9zimqUCzA) was used.

Favicon generated by [Favicon generator](https://www.favicon-generator.org/)

The icons in the header and footer were taken from [Font Awesome](https://fontawesome.com/). Fonts are from [Google fonts](https://fonts.google.com/).

The content is based on content from [Reading Museum](https://www.readingmuseum.org.uk/), [Wikipedia](https://en.wikipedia.org/wiki/Reading_Abbey) and [Berkshire War memorials](http://www.berkswm.org/index.html). 

The Gallery styling was done with the assistance of my Code Institute mentor, Rory Patrick Sheridan.

The Photos are my own, with background image colouring was done by Tanith Griffiths.