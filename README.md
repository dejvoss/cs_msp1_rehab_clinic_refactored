# Rehabilitation Clinic Website
Stream One Project: User-Centric Frontend Development - Code Institute

This is the website for my friend Ewelina who is a manual therapist. She just start running her own rehabilitation clinic and she would like to have own website. I offer her to create a website to practice my skills due to first milestone project during Full Stack Web Developer course.
Website cover 6 sections - home, for whom, treatments, recommendations, gallery and contact.

## Demo
 A live website can be found [here](https://dejvoss.github.io/code-inst-ms1-project/).


## UX


### User stories

Ewelina: I expect to show for people what treatments i am doing and how to found me in my City.

User2: As a person who is looking for physioterapis i expect to see where to find clinic, what to expect from it and how to easy make appointment.


### Strategy

It is a going to be company/ therapist website for local city clients. The main goal of the web is to raise number of patients. They are the local people with back and joint injuries. Audience are mostly the people in age 30-60 from different culture, they do different jobs, but many often time is a sitting position job - drivers, office people. They are suffering for back, spin and muscles pains, but also people with posture defects. Audience are looking for therapy, they want to know what treatments are in the clinic, they want to see good references about. It is important for users to know how to found clinic and how to make a visit, they need to see the possibility for online registration.
it should be very visible on web what health ailments are being treated in the clinic

My goal in design was to make a easy, minimalist and user-firendly website, but also modern and different one. I decide to do one page web with big nice pictures which shows pain, body parts, but also happiness as a result of therapy. I wanted to place pictures which will be familiar to the users.
I chose to show what ilness can be treated in clinic and what type of therapies are there. I choose to have good quality pictures with not too much text descriptions. 
It was very important to me to put the recommendation section with picture which show happiness.
One of the main goal was also to have clear view of the place - so i decide to paste the picture from google map with link to it. 


### Scope
People said they need to see certifications, the person to whom they can trust.
People actually need to know that the therapy will help them.
People doesn’t know that they want to see the other people happy from therapy.
website contain requirements:
 - name of cabinet
 - short description of what we do
 - list of treatments 
 - description of treatments 
 - address with map 
 - make an appointment online
 - reasons for therapy
 - recommendations
 - photo of happy clients
 - photo of people with pain


### Structure
I wanted to have nice big pictures referring to rehabilitation and all information in one page.

[structure](https://github.com/dejvoss/code-inst-ms1-project/blob/master/structure.JPG)

[hub_sub_navigation](https://github.com/dejvoss/code-inst-ms1-project/blob/master/hubsubnav.JPG)

### Skeleton
[1st view](https://github.com/dejvoss/code-inst-ms1-project/blob/master/skeleton.JPG)


### Surface
Different green color type was choosen due to colors of clinic logo.


## Technologies
1. HTML
2. CSS
3. Bootstrap (4.4.0)
4. Favicons
5. Google Fonts
6. [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)
7. collapse by Bootstrap
8. Menu by bootstrap.


### Features
This site is a one page site. Sections are splitted by different full height pictures. Navigation bar is collapsed and is opened in top in row direction on big screens and column direction in small screens. Each section has a background picture or use the picture from home section.



### Features left to Implement
In the future i would like to add:
1. Instead of scrolling from section to section i would like make animation which will show each section one by one.
2. Add posibilities for users to make online appointment and phone appointment.


## Testing

Performance test done in [PageSpeedInsights](https://developers.google.com/speed/pagespeed/insights/) with result of 97 for mobile and 99 for desktop.

I test all links by myself.

Using of website was tested by Ewelina, my wife and people in slack. I've got good feedback which shows me issues to solve. Some of the comments and solutions i place below. Due to lack of hardware i couldn't test it on the very big screen.
Mobile tests was done in Android 9.
Desktop tests was done in google chrome 79.0.3945.88, firefox 71.0, microsoft edge 10, and safari 5.1.7. 
Test in safari browser was failed. 

1. Mobile version:

User1: Links in footer are different than in navigation bar, Contact link in footer doesn't work.

User2: White background below logo looks odd. Maybe is good to remove it and change font for bigger instead. - Done and looks really better.
The address information on white background in contact/map section is to big, could be better without it. - Done and it is better.

User3: The drop down menu, it’s nice, works lovely.... but the colour scheme is very similar to some of the background images. When you click on the options, moving on the main page, it makes reading the menu options hard and so. - solution implemented - change the menu color for not transparent and it is looks better.

User4: Images in gallery are so small. - implemented the lightbox to solve it.

2. Desktop version:

User1: In recommandation section is a lot of empty space. - solved by remove restriction of section height.

User2: Map picture is small if compare to the gallery pictures.

User3: Types of treatments in for who section are opened all ugly, maybe will be better to have close one when other is opening. - solved.

## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/dejvoss/code-inst-ms1-project.git` into your terminal.

### Content
All content in the "For whom" and "Treatments" sections in this website were taken from google and wikipedia. 
All content in the "Recommendations" sections were taken from google place recommendation.


### Media
All photos were taken from [secret stock 99](https://shop.stockphotosecrets.com/), a stock image library.


### Acknowledgements
The Lightbox was suggested by my mentor and applied from [here](https://lokeshdhakar.com/projects/lightbox2/)

The navigation bar, collapsed cards in for whom section and cards in treatment section was taken from [here](https://getbootstrap.com/docs/4.4/getting-started/introduction/)




