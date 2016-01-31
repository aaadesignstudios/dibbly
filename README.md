# Spotlight - App Landing Page #

Spotlight is a clean app landing page ideal for promoting your iOS and Android apps, as well as web services and software. Spotlight comes with 3 predefined layouts together with 3 default devices to showcase your product. Built with Bootstrap 3, it is fully responsive and looks perfect on all major browsers, tablets and phones.

### Available devices ###

* iPhone 6s
* Samsung Galaxy S5
* Macbook

### Available layouts ###

* Dark layout
* Light layout
* Multicolor layout

### Key features ###

* Fully Responsive
* Functioning contact form
* Spam protection by noCaptcha
* LESS files included
* Clean & developer friendly code
* Free updates
* Free support

All images and plugins used in this template are FREE for personal and commercial use.



### Stay tuned ###

Follow us on Twitter to instantly know of new templates and updates released:   

https://twitter.com/YevSim   

If you like our works, feel free to contact us with new feature requests or ideas for future templates:   

http://simpleqode.com/#contact   

Your feedback would be highly appreciated.  


### Instructions ###

** General **   

*  How do I edit the styles?   

You can either work with vanilla .css or source .less files included. For vanilla .css, please open assets/css/styles.css (or styles_light.css if you use the light layout). Source .less files are located at assets/less/. If you work with .less files, after the changes are done, you only need to compile the main styles.less file located at assets/less/styles.less. This is the main .less file that imports all of the other .less files (including original Bootstrap source .less files). For the light layout, the last line in the styles.less file (@import "light-version.less";) should be uncommented. Please visit http://lesscss.org/usage/index.html#third-party-compilers to find out how you can compile .less files to .css.

*  How do I create a different color scheme (the light layout only)?

You can easily create your own color scheme in a matter of one minute. Please follow the steps below: 

1) Open assets/less/colors.less and change the value of the single global LESS variable: @brand-primary.    
2) Recompile .less files.


** Contact form **

*  How do I set up the contact form?

This template contains a fully functioning PHP contact form with spam protection powered by reCaptcha. Note: The contact form will not work in your local environment without a server that supports PHP. In order to set up the contact form, please follow the steps below:

1) Open config.php and fill out the required information:

 - reCaptcha Site ($publickey) and Secret ($privatekey) keys

Please go to https://www.google.com/recaptcha/admin/create if you don't have the keys yet.

 - Sender name and email address ($mail_sender)

This is a name and email address you will see in the "From:" line of new emails you will receive.

 - Your email address ($to_email)

This is an email address new emails will be sent to.

 - Email subject ($mail_subject)

This is a subject of new emails you will receive.

2) Insert your reCaptcha Site key (see Step 1) in the index HTML file:


```
#!html

<div class="g-recaptcha" data-sitekey="YOUR_SITE_KEY"></div>
<!-- (e.g. <div class="g-recaptcha" data-sitekey="09sdv0sf9v0sdf9b0df9b09dfb"></div>) -->
```

3) Save all files.

** Miscellaneous **  

* How do I choose a different from the default device?   

1) Please open your index HTML file and find the .device__container block.  


```
#!html

<!-- Devices -->
<div class="device__container hidden-xs">
  <div class="iphone__container black"> ... </div>
  <div class="samsung__container black hidden"> ... </div>
  <div class="macbook__container hidden"> ... </div>
</div>
```

2) Remove the .hidden class from the container of the device, that you want to enable. Add the .hidden class to the container of the default device (iphone). Additionally add a .black or .white class to change the device color (works for phones only).   

* How do I choose different colors for the multicolored layout backgrounds?   

1) Please open your index HTML file and find this line: 


```
#!html

<!-- Background Colors -->
<div class="bg-colors hidden" data-colors="#568CD3,#D3744C,#389E86,#9356D3,#D35D56,#587EA0,#518E7E"></div>
```

List your colors in the data-color attribute followed by a comma in the order you want them to appear on your page. The number of colors in the data-color attribute should be equal to the number of sections on the page.

Feel free to contact me if you have any questions: http://simpleqode.com/


### Sources and credits ###

*  Twitter Bootstrap

URL: http://getbootstrap.com/  
AUTHOR: @mdo and @fat  
LICENSE: MIT License  

** Plugins **

*  Font Awesome

URL: http://fontawesome.io/  
AUTHOR: Dave Gandy  
LICENSE: MIT license  

*  CSS Animation

URL: https://daneden.me/animate/  
AUTHOR: Dan Eden  
LICENSE: MIT license  

*  fullPage.js

URL: http://alvarotrigo.com/fullPage/   
AUTHOR: Alvaro Trigo   
LICENSE: MIT License   

*  Slimscroll

URL: http://rocha.la/jQuery-slimScroll   
AUTHOR: Piotr Rochala   
LICENSE: MIT License   

** Images **

*   bg_1.jpg, bg_2.jpg, /site-screenshots   

URL: http://unsplash.com/    
LICENSE: Creative Commons Zero   

*   iphone_black.png, iphone_white.png, samsung_black.png, samsung_white.png, macbook.png (including .psd files)  

URL: http://www.pixeden.com/   
AUTHOR: Pixeden.com     
LICENSE: Royalty free for use in both personal and commercial projects    

*   /app-screenshots   

URL: http://freebies.designzway.com/   
AUTHOR:  Olia Gozha    
LICENSE:  Free for both personal & commercial use   

*   Video file

URL: https://vimeo.com/63844761      
AUTHOR: Alex Penny
LICENSE: Creative Commons  



### Changelog ###

Version 1.0.1 - 21/12/2015

* Dark Layout made default (no update required)

Version 1.0.0 - 11/12/2015   

* Initial release