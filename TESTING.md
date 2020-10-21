# Bossa&Morna Webiste - Testing Details

[Main README.md file](README.md)

[Github repository](https://github.com/Claudio-C-Santos/Milestone-Project-1.git)

## Code Validation

- [W3C HTML Validation Service](https://validator.w3.org/)

All the HTML file were validated via Jigsaw's validation service and it showed no errors were found.

- [W3 CSS Validation Service](https://jigsaw.w3.org/css-validator/)

The style.css file was validated via Jigsaw's validation service and it showed no errors were found being certified by the icon below.

<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

## Testing User Stories from UX section of README.md

For these tests please remit to "Features" section on [README.md](README.md). In that section, there are gif elements demonstrating how to use each feature based on the user stories.

## Manual testing of all elements and functionalities throughout the Website

All the pages, sections and elements have been successfully tested for responsiveness with Dev Tools using desktop (1024px), tablet (768px) and mobile (320px) views. Tests performed on Chrome, Microsoft Edge and Mozilla Firefox.
Requested several friends and family to test the website on their devices and feedback was that everything was working correctly and looked good. Note that they didn't know what the website should look like.
For all the forms along the website, Code Institute's form dump was used (https://formdump.codeinstitute.net/).


### Fixed elements - Navigation Bar & Footer

- Navigation bar
    1. This bar is successfully displayed in every page of this website.
    2. When in mobile view the navigation bar collapses into a toggle button.<br>
    _While testing the logo overflowed the bar, This was fixed with adjusting the logo's size. The same hapenned with Contact Us button._ 
    3. The logo works successfully as a link to Home page in every page of the website. On purpose broke the link to the image and alternative text is displayed.   
    4. Contact Us button successfully changes style when hovered on on desktop view.
    5. All the links on the navigation bar have been tested successfully. The location in the website is given by a higher font weight.

- Footer
    1. This bar is successfully displayed in every page of this website.
    2. When in mobile view the elements successfully adjust.
    _Had to changes newsletter subscription form's style for mobile views so it looks better_
    3. Links to social media successfully change their style when hovered on desktop view. This doesn't happen on tablet and mobile views.
    4. Links to social media profiles successfully opens the link in a new page in the browser.
    5. Email address is mandatory in newsletter subscription input when clicking on subscription button.  

### Home

- New Album section
    1. Pre-order button successfully changes style when hovered and links to the form page.
    2. Album image's animation successfully displayed. 
    3. When in mobile view, the image successfully relocates under the text and pre-order button.

- Image carousel
    1. Successfully runs in all referred browsers.

- Contact
    1. Contact Us button successfully changes style when hovered. In mobile and tablet views the button's style is the same as when hovered.

### Band

- About band text
    1. Headers and text adjust to different screen sizes.

- Artist Biography
    1. The links to the artist's personal social media profiles successfully opens in a new page in browser. There's a link on each icon and on the text.
    2. The elements adjust successfully in every screen size.

### Gallery

- Videos
    1. Embedded iFrames from Youtube play correctly.

- Photos
    1. The photos adjust successfully in differente screen sizes.

### Calendar

- Event Cards
    1. Cards size adjust successfully to screen size.
    2. Add to Calendar button successfully changes style when hovered.
    3. Modal successfully pops up whenever Add to Calendar button is clicked.

### Forms

- Contact Us
    1. Left navigation column is not displayed when in mobile view.
    2. When in tablet and desktop views, the buttons successfully link between Contact Us and Pre-Order forms. They also successfully change style when hovered.
    3. Form doesn't allow to be submitted without first and last names, correct email address and message. This is done by included "require" in each element, the only one is not required is date.
    4. When details are correctly inserted, the form successfully submits it in Code Institute's form dump.
    5. Send button successfully changes style when hovered.

- Pre-Order
    1. Left navigation column is not displayed when in mobile view.
    2. When in tablet and desktop views, the buttons successfully link between Contact Us and Pre-Order forms. They also successfully change style when hovered.
    3. Form doesn't allow to be submitted without first and last names and correct email address. The payment method is Direct Debit by default but can be changed.<br>
    _On Firefox and Edge the radio button follows the label's style however on Chromes this doesn't happen. Wasn't able to change this._
    4. When details are correctly inserted, the form successfully submits it in Code Institute's form dump.
    5. Submit button successfully changes style when hovered.

    