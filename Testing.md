Eco SanitAl web page has been tested using the following:

- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator)
        - [Home Page](#home-page)
        - [Services](#services-page)
        - [Gallery Page](#gallery-page)
        - [Contact Page](#contact-page)
    - [W3C CSS Validator](#w3c-css-validator)
- [Lighthouse](#lighthouse)
- [Responsiveness](#responsiveness)
- [Browser Compatibility](#browser-compatibility)
- [Testing User Stories](#testing-user-stories)
    - [Prospective Visitors](#prospective-visitors)
    - [Business Owners](#business-owners)
- [Bugs](#bugs)
    - [Resolved](#resolved)
      
  
# Code Validation
## W3C HTML Validator


Eco sanitall website passed all tests using the W3C HTML Validator tool


### Home Page

<img width="1105" height="173" alt="index" src="https://github.com/user-attachments/assets/08ab4e76-ae9a-4791-9886-f36e5b712c31" />

### Services Page

<img width="1310" height="151" alt="services" src="https://github.com/user-attachments/assets/88cf201a-006f-4222-8f3e-2460d4c4de79" />

### Gallery Page

<img width="1310" height="195" alt="gallery" src="https://github.com/user-attachments/assets/34e5a655-ceea-4736-a588-bf67e8b33967" />

### Contact Page

<img width="1310" height="195" alt="contact html" src="https://github.com/user-attachments/assets/23952995-f512-4948-b747-7ba3db79aa0d" />

## W3C CSS Validator

The website passed all tests using the W3C CSS Validator tool
<url="https://jigsaw.w3.org/css-validator/validator$link">
or
<url="https://jigsaw.w3.org/css-validator/check/referer" (for HTML/XML document only)>

# Lighthouse

### Lighthouse Report for Homepage (Desktop)

<img width="997" height="249" alt="lighthouse-desktop" src="https://github.com/user-attachments/assets/ac85a523-0594-442c-8740-7352fbb359c8" />

### Lighthouse Report for Homepage (Mobile)

<img width="1029" height="203" alt="lighthouse-mobile" src="https://github.com/user-attachments/assets/e9c7d083-2db6-4736-81e4-0839a84a605c" />

I used Lighthouse in Google Developer Tools to examine the pages of the website in general:
- Performance
- Accessibility
- Best Practices
- SEO
All Pages performed well in:
- Performance, Accessibility, Best Practices and SEO on Desktop
- Accessibility, Best Practices and SEO on Mobile
Some Pages did not perform as well (scored 80 and above) in:
- Performance on mobile
Lighthouse recommends better images. (Detailed in [Unresolved Bugs](#unresolved) section)

# Browser Compatibility

The site was tested in Google Chrome (my laptop). It was also tested in Google Chrome and Safari on mobile/tablet, with no apparent problems.
- The font appearance seems to change on some occasions but it doesn't affect overall web page performance..

# Responsiveness

Responsivity tests were done by using Google Chrome DevTools.  
Device screen sizes covered include:
- iPhone SE
- iPhone XR
- iPhone 12 Pro
- Pixel 5
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Mini
- iPad Air
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51/71
- Nest Hub
- Nest Hub Max

# Testing User Stories

## Prospective Visitors

- As a prospective customer I would like to see jobs done by this company, so I can decide if I want to book one of their services. 
    * A good way to do that is using social media, reviews and gallery on  the website along with information.
    - As a prospective visitor I would like to see what other services this company offers compared to others. There are many cleaning companies in London so what makes this one stand out.
   *  By checking our website section Why us? You will find many good reasons to request our services. Also there are added icons so it helps visually understand the contempt of our strenghts.
    - As a prospective visitor I would like to be able to contact the company directly for any information. As it is really time consuming when you have to look up on a few pages online for a company number.
   *  There are many ways to look for our contact details, check out our webpage!

## Business Owners

* As the business owner, I want my website to be accessible and user-friendly on any device.
    - The website design is responsive so remains aesthetically pleasing and functional on all screen sizes. The pages also feature meta descriptions and alt-text which is beneficial for SEO.

* As the business owner, I want my website to feature external links to my social media channels.
    - There are links to social media channels in the footer bar, which appears on every page. And there is contact information on the contact page, just in case.

# Bugs

## Resolved
- I went through several trial and error processes with the card section. I attempted to put the cards next to each other on medium and larger screens but wasn't able to, considering I faced so many hardships lately that delayed me doing my studies/project I decided to do things differently and change css stylings.
- The HTML validator flagged that there were issues with some selectors not closed properly or some just left around. I formatted the text and used the grid to check if everything was in place.
- The HTML validator flagged that I have an "unnecessary tag on my navbar” but it doesn't affect usage and I remembered that from the example box that's how it was spelled. So no changes were made there.
- When viewing the images on larger devices the image gets pixeled a bit but as I mentioned I could not use my source image as the laptop keyboard is stuck and I cant write password to access it as the letter keeps on filling the password section without anyone touching. So as I couldn't have a pictureless website I used what I had.


Back to [README.md](/README.md#testing)
