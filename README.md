Welcome! [Code Institute](https://codeinstitute.net)

# Forty Fathom Freedivers

Forty Fathom Freedivers is a fictious group of free-divers based in the southwest of Ireland. They love to go out in the cold Atlantic water and dive the many coves and bays there. Forty Fathoms might be a bit ambitious for this motely crew, but that's their ambition.

The Forty Fathom Freedivers would like to share their knowledge, skills and probably a few hot whiskeys with anyone - beginner or seasoned - who dares face the cold waters.

Their sales-pitch might not be great, and the truth may be slightly 'alternative', but as this is their first attempt at a website it can only improve in the future. The free-divers like to keep the intro as jolly and non-technical as possible so as not to scare potential members away.


![Responsive Mockup](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/ami-responsive.PNG)

## Features 

This web site consists of three pages:
- The landing page introduces the person browsing the site to the group, who they are and why one should join them
- The Zen page explains some of the virtues of free-diving for one's health and the sheer beauty of the ocean
- The Join Us page allows one to join the group for a free-diving session


### Existing Features

- __Navigation Bar__

  - The Navigation bar is responsive and appears on each page
  - Additionally, I embedded links to the Zen and Join-Up pages in the text of the landing page, which provide a short-cut for those who want to go straight from there.

- __The Landing Page__

  - This page introduces the user to the Forty Fathom Freedivers website with a rather chilly image of a free-diver among some huge marine plants (courtesy of vcereporter)
  - The landing page wets the appetite launches the user to the Zen and Join Us pages

![Landing Page](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/fff-index.PNG)

- __Zen page__

  This page introduces the user to some of the experiences on offer, divided over three frames:
  - The Mammalian Diving Reaction with a background image of a seal (courtesy of scubadiverlife.com)
  - Breathing techniques with a background image of a person in the lotus position (courtesy of yoga history)
  - The Beauty of the Irish Atlantic with a background image of one of tha Aran islands (courtesy of Aran-islands-craic)

  The background of the page is a beautiful underwayer image taken by Viktor Tar

![Zen text](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/fff-zen.PNG)

- __Join Us page__

  - This page has a beautiful background image of the famoud free-diver Guillaume Nery among sharks (courtesy of CNN.com)
  - the join-up form allows allows one to enter name, address, e-mail address, their experience with free-diving and any material they might need when contavted for a dive

![Meetup Times](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/fff-join-us.PNG)

- __The Footer__ 

  - The footer section provides links to all the major social media sites

![Footer](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/fff-footer.PNG)

## Testing 

I have test the code in Chrome, Firefox and MS Edge and checked responsiveness for a variety of screen widths in all browsers.

I tried it with Safari for Windows 10 but the page would not load and gave no errors.

I also tried it on my tablet (Lenovo) and smartphone (Samsung SM-G950F), both Android devices, and the responsive design worked.

### Validator Testing 

- HTML
  - Tested and found good with [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fplatypus2022.github.io%2FPortfolio_Project_1%2F). 


- CSS
  - Tested and found good with [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fplatypus2022.github.io%2FPortfolio_Project_1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).



### Performance

Lighthouse was used to test performance and gave the following scores:

![Lighthouse](https://github.com/Platypus2022/Portfolio_Project_1/raw/main/assets/images/lighthouse-performance.PNG)


### Unfixed Bugs

I tried to fix the performance issue where caching is recommended (/*<meta http-equiv="cache-control" content="public">
    <meta http-equiv="cache-control" max-age="31536000">*/), but this did not work.
I am aware that as I am using a lot of images as background, if these do not load, a dark schreen should be loaded in their place. I tried this with using background-color: black, just before the image url in CCS but it did not work.
I noticed a bit late that my screen grabber put the png file extensions in uppercase. I tried to change this to lowercase after I had pusthed the files to Github but this gave the following error:

        gitpod /workspace/Portfolio_Project_1 (main) $ git push
        To https://github.com/Platypus2022/Portfolio_Project_1.git
         ! [rejected]        main -> main (fetch first)
        error: failed to push some refs to 'https://github.com/Platypus2022/Portfolio_Project_1.git'
        hint: Updates were rejected because the remote contains work that you do
        hint: not have locally. This is usually caused by another repository pushing
        hint: to the same ref. You may want to first integrate the remote changes
        hint: (e.g., 'git pull ...') before pushing again.
        hint: See the 'Note about fast-forwards' in 'git push --help' for details.

The file extensions are therefore in uppercase instead of the preferred lowercase.

## Deployment



- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Main Branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://platypus2022.github.io/Portfolio_Project_1/


## Credits 

Credits mostly to Code Institute for bringing me this far.


### Content 


- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- Thanks to the follow sites for the photos:
-   Aran-islands-craic
-   vcereporter
-   CNN
-   Scubadiverlife
-   viktor-tar-underwater
-   Yoga-history.com



