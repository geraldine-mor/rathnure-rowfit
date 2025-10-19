# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| File | URL | Screenshot | Notes |
| --- | --- | --- | --- |
| [404.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/404.html) | ![screenshot of no errors message](documentation/testing/404-validation.png) |  |
| [contact.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/contact.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/contact.html) | ![screenshot of contact page errors](documentation/testing/contact-page-errors.png) ![screenshot of no errors message](documentation/testing/contact-validation.png) | html validation showed 3 errors these were easy fixes and retesting showed no errors |
| [gallery.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/gallery.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/gallery.html) | ![screenshot of no errors message](documentation/testing/gallery-validation.png) | |
| [index.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/index.html) | ![screenshot of errors](documentation/testing/homepage-code-validation-errors.png) ![screenshot of trailing slash info messages](documentation/testing/trailing-slash-message.png) ![screenshot of no errors message](documentation/testing/index-validation.png) | Initial validation testing showed some issues which were fixed. Accidentally formatting the document with Prettily created trailing slashes which have now been removed |
| [success.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/success.html) | ![screenshot of no errors message](documentation/testing/success-validation.png) |  |
| [timetable.html](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/timetable.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://geraldine-mor.github.io/rathnure-rowfit/timetable.html) | ![screenshot of no erros message](documentation/testing/timetable-validation.png) |  |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [styles.css](https://github.com/geraldine-mor/rathnure-rowfit/blob/main/assets/css/styles.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://geraldine-mor.github.io/rathnure-rowfit) | ![screenshot](documentation/testing/css-validation.png) |  |


## Responsiveness

I tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot of home page mobile view](documentation/testing/home-mobile.png) | ![screenshot of home page tablet view](documentation/testing/home-tablet.png) | ![screenshot of home page desktop view](documentation/testing/home-desktop.png) | Displays as expected on mobile, tablet and desktop screens. All links work as expected. |
| Timetable | ![screenshot of timetable page mobile view](documentation/testing/timetable-mobile.png) | ![screenshot of timetable page tablet view](documentation/testing/timetable-tablet.png) | ![screenshot of timetable page desktop view](documentation/testing/timetable-desktop.png) | Displays as expected on mobile, tablet and desktop screens. All links work as expected. |
| Gallery | ![screenshot of gallery page mobile view](documentation/testing/gallery-mobile.png) | ![screenshot of gallery page tablet view](documentation/testing/gallery-tablet.png) | ![screenshot of gallery page desktop view](documentation/testing/gallery-desktop.png) | Displays as expected on mobile, tablet and desktop screens. Header and footer links work as expected. |
| Contact | ![screenshot of contact page mobile view](documentation/testing/contact-mobile.png) | ![screenshot of contact page tablet view](documentation/testing/contact-tablet.png) | ![screenshot of contact page desktop view](documentation/testing/contact-desktop.png) | Displays as expected on mobile, tablet and desktop screens. All form fields are required, buttons and links work as expected. |
| Success | ![screenshot of success page mobile view](documentation/testing/success-mobile.png) | ![screenshot of success page tablet view](documentation/testing/success-tablet.png) | ![screenshot of success page desktop view](documentation/testing/success-desktop.png) | Displays as expected on all sizes, all links work as expected. |
| 404 | ![screenshot of 404 page mobile view](documentation/testing/404-mobile.png) | ![screenshot of 404 page tablet view](documentation/testing/404-tablet.png) | ![screenshot of 404 page desktop view](documentation/testing/404-desktop.png) | Displays as expected on all sizes, all links work as expected. |

## Device Testing

I tested the deployed site on 3 different devices: an iphone SE 2020, a Samsung Galaxy Tab S7 and a Windows laptop with additional xxl scren. All pages rendered as expected and all links and buttons worked as intended. 
>Screen sizes were taken from [viewportsizer.com](https://viewportsizer.com/what-is-my-screen-size/). 

|  | iPhone SE (2020) | Samsung Galaxy Tab S7 | Windows 10 Laptop | Additional Dell Monitor |
| --- | --- | --- | --- | --- |
| Size| 375 x 544 | 753 x 1068 | 1351 x 607| 1665 x 923 |
| Home | ![screenshot of homepage with menu options on mobile](documentation/testing/mobile-test-menu.png) | ![screenshot of homepage on tablet](documentation/testing/tablet-test-home.jpg) | ![screenshot of homepage on desktop](documentation/testing/desktop-test-home.png) | ![screenshot of homepage on xxl screen](documentation/testing/xxl-test-home.png) |
| Timetable | ![screenshot of timetable on mobile](documentation/testing/mobile-test-timetable.png) | ![screenshot of timetable on tablet](documentation/testing/tablet-test-timetable.jpg) | ![screenshot of timetable on desktop](documentation/testing/desktop-test-timetable.png) | ![screenshot of timetable on xxl screen](documentation/testing/xxl-test-timetable.png) |
| Gallery | ![screenshot of gallery on mobile](documentation/testing/mobile-test-gallery.png) | ![screenshot of gallery on tablet](documentation/testing/tablet-test-gallery.jpg) | ![screenshot of gallery on desktop](documentation/testing/desktop-test-gallery.png) | ![screenshot of gallery on xxl screen](documentation/testing/xxl-test-gallery.png) |
| Contact | ![screenshot of contact page on mobile](documentation/testing/mobile-test-contact.png) | ![screenshot of contact page on tablet](documentation/testing/tablet-test-form-validation.jpg) | ![screenshot of contact page on desktop](documentation/testing/desktop-test-contact.png) | ![screenshot of contact page on xxl screen](documentation/testing/xxl-test-contact.png) |
| Success | ![screenshot of success page on mobile](documentation/testing/mobile-test-success.png) | ![screenshot of success page on tablet](documentation/testing/tablet-test-success.jpg) | ![screenshot of success page on desktop](documentation/testing/desktop-test-success.png) | ![screenshot of success page on xxl screen](documentation/testing/xxl-test-success.png) |
| 404 | ![screenshot of 404 page on mobile](documentation/testing/mobile-test-404.png) | ![screenshot of 404 page on tablet](documentation/testing/tablet-test-404.jpg) | ![screenshot of 404 page on desktop](documentation/testing/desktop-test-404.png) | ![screenshot of 404 on xxl screens](documentation/testing/xxl-test-404.png) |

## Browser Compatibility

I tested my deployed project on 3 different browsers to  check for compatibility issues. There were minor differences on the contact form described below but as these are browser default settings, I am happy that the project still looks and functions as intended across all 3 browsers.

| Page | Chrome | Firefox | Safari (on iphone) | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot of homepage on chrome](documentation/testing/chrome-home.png) | ![screenshot of homepage on firefox](documentation/testing/firefox-home.png) | ![screenshot of homepage on safari](documentation/testing/safari-home.png) | Works as expected |
| Timetable | ![screenshot of timetable on chrome](documentation/testing/chrome-timetable.png) | ![screenshot of timetable on firefox](documentation/testing/firefox-timetable.png) | ![screenshot of timetable on safari](documentation/testing/mobile-test-timetable.png) | Works as expected |
| Gallery | ![screenshot of gallery on chrome](documentation/testing/chrome-gallery.png) | ![screenshot of gallery on firefox](documentation/testing/firefox-gallery.png) | ![screenshot of gallery on safari](documentation/testing/mobile-test-gallery.png) | Works as expected |
| Contact | ![screenshot of contact form on chrome](documentation/testing/chrome-contact.png) | ![screenshot of contact form on firefox](documentation/testing/firefox-contact.png) | ![screenshot of contact form on safari](documentation/testing/safari-contact.png) | All 3 browsers display the form field required message slightly differently and also the radio button has subtle differences across all 3 browsers. These differences are acceptable. |
| Success | ![screenshot of success page on chrome](documentation/testing/chrome-success.png) | ![screenshot of success page on firefox](documentation/testing/firefox-success.png) | ![screenshot of success page on safari](documentation/testing/mobile-test-success.png) | Works as expected |
| 404 | ![screenshot of 404 page on chrome](documentation/testing/chrome-404.png) | ![screenshot of 404 page on firefox](documentation/testing/firefox-404.png) | ![screenshot of 404 page on safari](documentation/testing/mobile-test-404.png) | Works as expected |

## Lighthouse Audit

I tested my deployed project using the Lighthouse Audit tool to check for any major issues. There were accessibilty issues on the timetable & contact pages which have been corrected and are decribed further in [bugs](#bugs). Some warnings are outside of my control, and mobile results tend to be lower than desktop. Best practice and SEO reductions on the 404 page are as a result of the filepath being broken in order for the page to load.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-home-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-home-desktop.png) |
| Timetable | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-timetable-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-timetable-desktop-fixed.png) |
| Gallery | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-gallery-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-gallery-desktop.png) |
| Contact | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-contact-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-contact-desktop.png) |
| Success |  ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-success-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-success-desktop.png) |
| 404 | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-404-mobile.png) | ![screenshot of lighthouse report](documentation/lighthouse/lighthouse-404-desktop.png) |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | 
| --- | --- |  --- |  --- | 
| Home | Feature is expected to display information about the club and indoor rowing | Verified that the page displays information about the club and indoor rowing in a clear and concise manner. | The mission and purpose were displayed as expected. |
| | Feature is expected to have accessible navigation links. | Checked navigation and button links for correct functionality and accessibility. | All links were functional and accessible. |  |
| | Feature is expected to be fully responsive. | Resized the browser window and tested on multiple devices (mobile, tablet, desktop). | The page was responsive across all tested screen sizes. | 
| Testimonials| Feature is expected to show member feedback. | Verified that the page displays member testimonials. | Testimonials displayed as expected. |
| Timetable | Feature is expected to show the club timetable for classes. | Confirmed that the page contains a structured table or list with class timings. | Timetable was displayed as expected. | 
| Pricing | Feature is expected to display details pricing options in a clear and concise manner. | Verified that the page contains a table or list of pricing options. | Pricing options were displayed as expected. |
| Gallery | Feature is expected to showcase a gallery of club classes, activites and past events. | Verified that the gallery contains clear images that aren't stretched or pixelated, and are fully responsive. | Images are properly sized, and respond well to different device sizes. |
| Contact Form | Feature is expected to prevent submission of an empty form. | Attempted to submit the form without filling any fields. | Form submission was blocked, as expected. | 
| | Feature is expected to enforce valid input types for each field. | Entered invalid data (e.g., random text in an email field, numbers in a name field, etc.). | Error messages were displayed appropriately, and submission was blocked. | 
| | Feature is expected to deliver a confirmation message to inform the user that the form has been submitted. | Completed all fields with valid data. | On submit a new page opened with a success message and links back to the site. | 
| Social Links | Feature is expected to include working links to the club’s social platforms (Instagram, Facebook, etc.). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | 
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/test`) to test error handling. | A custom 404 error page was displayed as expected. | 

## User Story Testing

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a potential member | I want to be able to easily navigate the site | so that I can find all the information I need to decide whether to join. | ![screenshot of navbar](documentation/features/navbar.png) |
| As a local resident interested in joining the club | I want to see a clear image | so I can see what it is all about. | ![screenshot of hero image](documentation/features/hero-image.png) |
|As a local resident | I would like to know more about the club | so that I can decide if I want to try it. | ![screenshot of about section](documentation/features/about-section-desktop.png) |
|As a potential member | I would like to know when the classes are held | so that I can see if it works with my schedule. | ![screenshot of timetable](documentation/features/timetable-desktop.png) |
| As a potential member | I want information about how to contact the club | so that I can arrange to join. | ![screenshot of contact details](documentation/features/contact-details.png) |
| As a local resident | I want to contact the club because I have specific questions I need answered | so that I can decide whether to attend. | ![screenshot of contact form](documentation/features/contact-form.png) |
| As a potential member | I would like to easily find the social media accounts for the club | so that I can look at their club activities and see if I think it will be a good fit for me. | ![screenshot of footer](documentation/features/footer-desktop.png) |
| As a potential member | I want to see images of classes and club events | to help me decide if I would like to join. | ![screenshot of gallery](documentation/features/gallery-xl.png) |
| As a potential member | I want to see class and membership pricing options | so that I can see if it meets my budget expectations | ![screenshot of pricing section](documentation/features/pricing.png) |
| As a potential member | I want to read other people's experiences with the club | to help me decide whether to join | ![screenshot of testimonials](documentation/features/testimonials-desktop.png) |
| As an existing member | I want to check upcoming events | so that I can plan to attend | *Classified as wont-have for this release* |
| As a local resident | I want to receive updates on the club activities | so that I can decide whether to particiate | *Classified as wont-have for this release* |
| As an existing member | I want to register for classes | so that I can ensure I will get a place | *Classified as wont-have for this release* |

## Bugs

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search/geraldine-mor/rathnure-rowfit?query=is%3Aissue%20is%3Aclosed%20label%3Abug&label=Fixed%20Bugs&color=green)](https://www.github.com/geraldine-mor/rathnure-rowfit/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I used [GitHub Issues](https://www.github.com/geraldine-mor/rathnure-rowfit/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/geraldine-mor/rathnure-rowfit/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/testing/closed-bugs.png)

### Unfixed Bugs

To the best of my knowledge all bugs have been found and resolved.

[![GitHub issue custom search](https://img.shields.io/github/issues-search/geraldine-mor/rathnure-rowfit?query=is%3Aissue%2Bis%3Aopen%2Blabel%3Abug&label=Unfixed%20Bugs&color=red)](https://www.github.com/geraldine-mor/rathnure-rowfit/issues?q=is%3Aissue+is%3Aopen+label%3Abug)

### Known Issues

| Issue | Screenshot |
| --- | --- |
| The project is designed to be responsive from `320px` and upwards, in line with the material taught on the course LMS. Minor layout inconsistencies may occur on extra-wide (e.g. 4k/8k monitors), or smart-display devices (e.g. Nest Hub, Smart Watches, Gameboy Color, etc.), as these resolutions are outside the project’s scope, as taught by Code Institute. | ![screenshot](documentation/testing/smartwatch.png) |
| When validating the css, there were warnings about the css variables not being checked due to their dynamic nature. This is acceptable | ![screenshot of css warnings](documentation/testing/css-warnings.png) |

> [!IMPORTANT]  
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

