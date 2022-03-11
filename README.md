MetLif - Finance Landing Page Template
======================================

MetLif Documentation v1.0 by
[RadwanAnik](https://themeforest.net/user/radwananik)

------------------------------------------------------------------------
1.  [Getting Started](#line1)
    -   [Pages](#line1_1)
2.  [Page Settings](#line2)
    -   [Color Theme](#line2_1)
3.  [Extras](#line7)
    -   [Web Hosting](#line7_1)
    -   [Uploading to Server](#line7_2)
    -   [Optimization Tips](#line7_3)
4.  [Credits](#line8)
5.  [Changelog](#line9)
    -   [How to Upgrade](#line9_1)
    -   [Version 1.0](#v1_0)
6.  [Rate it](#line10)
7.  [Support](#line11)
8.  [Vote of Thanks](#line12)

Introduction

------------------------------------------------------------------------

-   **Item Name :** MetLif --- Finance Landing Page Template
-   **Item Version :** v 1.0
-   **Author :** [RadwanAnik](https://themeforest.net/user/radwananik)
-   **Help / Support :** [radwananik.ra\@gmail.com OR create
    ticket](hhttps://themeforest.net/user/radwananik)
:::

------------------------------------------------------------------------

<div>

First of all, Thank you so much for purchasing this template and for
being my loyal customer. **You are awesome!**\
You are entitled to get free lifetime updates to this product +
exceptional support from the author directly.

This documentation is to help you regarding each step of customization.
Please go through the documentation carefully to understand how this
template is made and how to edit this properly. Basic HTML and CSS
knowledge is required to customize this template. You may learn basics
from the links below.

**Learn HTML basics**

-   <http://www.w3schools.com/>
-   <https://developer.mozilla.org/>

#### Requirements to Customize this Template

You will need the following sofwares to customize this template.

1.  Code Editing Software (eg: visual studio code, Notepad++)
2.  Web Browser for testing (eg: Google Chrome or Mozilla Firefox)
3.  FTP Tool to upload files to Server (eg:
    [FileZilla](https://filezilla-project.org/download.php?type=client))

Be careful while editing the template. If not edited properly, the
design layout may break completely.\
If you have basic problem to customization mail
me(radwananik.ra\@gmail.com). No support is provided for faulty
customization.


Getting Started [\#back to top](#top)

------------------------------------------------------------------------

If you are able to read this documentation locally, which means you have
successfully downloaded the package and extracted the zip. The file
structure as follows :

``` {.brush:html}
    MetLif/
    ├── Help Docs/   
    ├── HTML/
    │   ├── css/
    │   │   ├── plugins/
    │   ├── images/  
    │   ├── js/  
    │   │   ├── plugins/  
    
                 
```

The folder you have to customize is the HTML folder. Copy `HTML` folder
from the package and paste it in your Project Folder. (This helps you to
prevent overwriting in original files. so if you messed up something,
you will get the original here.)

#### Pages [\#back to top](#top) {#line1_1 .sub-title}

Here are the list of HTML Pages included with this template

1.  Landing Style `index.html`

#### Color Theme [\#back to top](#top) {#line2_1 .sub-title}

By Default, this template uses color theme via css. By using css, it is
really easy to change the CSS Manually

Changing Color using css

1.  Open `/css/style.css` in your code editor
2.  find the class you would live to change. For example
    `.btn-danger: background: #4776E6;` from template class.
3.  Now copy the line and paste it in to your *style.css* file and then
    modify it.
4.  Now Save and Complie the CSS to see the changes
5.  Wohoo! You\'re done.
6.  If Ypur Face Any basic problem like color/image change e-mail us.

Extras [\#back to top](#top)

------------------------------------------------------------------------


#### Web Hosting [\#back to top](#top) {#line7_1 .sub-title}

Once you have finished all customizations, The next step is to upload
your Landing Page to a Live Hosting Server. For that you will need to
buy a Hosting Plan and a Domain name from a Service Provider.

#### Uploading to Server [\#back to top](#top) {#line7_2 .sub-title}

Once you have registered a domain name and Hosting, You will get FTP
details from your hosting provider. Use that login details to connect
with your server. You will need an FTP Software for this such as
[FileZilla](https://filezilla-project.org/download.php?type=client).
Connect with your server and open `/public_html` folder in your server.
Then copy all HTML, CSS and JS files from your local machine to your
root `/public_html` folder in your server. Please note the HTML files
should be in the Server\'s root folder. If your local project is in
`/your-folder/` Do not upload the folder directly. Instead open the
folder and select all HTML files and CSS, JS folders and upload.

#### Website Optimization Tips [\#back to top](#top) {#line7_3 .sub-title}

A Fast & Optimized Website has several factors which needs to be
implemented in order to achieve the desired results. There are several
Optimization Techniques available which will definitely affect your
Website\'s Performance in a Positive Way & we want to share a few of
them with you:

1.  #### gZip Compression & Browser Caching

    This is probably one of the Most Important Techniques you should
    definitely implement in order to bump up your Website\'s Loading
    Speed. **gZip Compression** is used to compress the Files that are
    delivered when loading a Website. It covers HTML, CSS, Javascript &
    Font Files along with other miscellaneous text files. Where as
    **Browser Caching** also covers Images & Videos apart from including
    the above files. This is used to saves the Static Data in your
    Browser itself so that when you open the Next Pages on the Same
    Website, the content does not gets Downloaded again, loading the
    Website fast.

    **gZip Compression** & **Browser Caching** can be enabled using the
    `.htaccess` File on an Apache Web Server. You can use the Codes from
    here:
    <https://github.com/h5bp/html5-boilerplate/blob/master/dist/.htaccess>
    to enable these modules on your server.

2.  #### Image Compression & Optimization

    We tend to use Lots of Images on our Websites but we often do not
    make efforts to Compress & Optimize them. Remember, the Larger the
    Image, the more time it takes to download and therefore this slows
    your website loading times affecting User Experience. Your customer
    will leave your website if it does not load within 3-5 Seconds which
    adversely affects your Sales. Therefore, it is important to Resize,
    Optimize & Compress your Images before using it on your Website.
    Here are some Tips which might come handy in optimizing images:

    1.  **Resize your Images:** Resize your Images before using it on
        your Website. Do not just Download an Image & place it as it is
        in your Website\'s `<img>` Tag without resizing it. The
        size/resolution of the Image matters since it is not recommended
        to use an Image size of `1200px` x `800px` in a Content Size of
        `300px` x `200px` as this is unnecessary. Resize it to `300px` x
        `200px`
    2.  **Image Formats:** There are three common file types that are
        used for web images which are JPEG, GIF, & PNG. For images with
        a Flat Background use **JPEG** images, for images with a
        Transparent background use **PNG** images and for images with
        Animations use **GIF** images.
    3.  **Compressing Images:** Images Compression is important as it
        considerably reduces the size without losing the quality. There
        are several FREE Image Optimization Tools available to
        Download.\
        **For MAC** use [ImageOptim](https://imageoptim.com/)\
        **For Windows** use [Riot](http://luci.criosweb.ro/riot/) for
        compressing JPEG Images & [PNG
        Gauntlet](http://pnggauntlet.com/) for PNG Images.

3.  #### CSS & jQuery Minifications

    It is also recommended that you **Combine & Minify** all your CSS
    Files to a single CSS File & all Javascript Files to a single JS
    File since **Minification** reduces the size of the File and
    **Combining** the files helps in reducing the number of HTTP
    requests made to the server. This is also an Important Factor in
    increasing the speed of your website. There are several tools
    available online to Minify your CSS & JS Files. Our recommendations
    are:\
    **For CSS** use [CSS Minifier](http://cssminifier.com/) and **For
    Javascript** use [Javascript
    Minifier](http://javascript-minifier.com/).

4.  #### Content Delivery Network

    You can use a **CDN** to further speed up your website. You can use
    the CDN to deliver static files of your website like CSS, JS, Images
    & Font Files. There are several CDN Hosting Providers available on
    the Internet but we would recommend
    [MaxCDN](https://www.maxcdn.com/) or
    [CloudFlare](http://www.cloudflare.com/). [Note:]{.label
    .label-danger} CDN setup requires Extra monthly Fees to setup, so it
    is completely optional & according to your needs. Cloudflare also
    has a Free plan, you can try that for free.

5.  #### Fast Web Hosting Servers

    A lot depends on your Web Hosting Servers, so it is recommended that
    you choose a Hosting Company/Server that provides a Reliable & a
    Fast Hosting Service. You can also choose our shared hosting plans.
    See above.

[Check Google Page
Speed](https://developers.google.com/speed/pagespeed/insights/){.btn
[Check Gtmetrix Grade](https://gtmetrix.com/){.btn

Credits [\#back to top](#top)

------------------------------------------------------------------------

We are really thankful to the makers of the frameworks, plugins and
images below. We used these to make this Landing Page more functional.
Demo images, you have seen in Live Demo is not included in the download
package because of their copyright restrictions.

#### Frameworks

1.  [Bootstrap](http://getbootstrap.com/)

#### Libraries

1.  [jQuery](http://jquery.com/)

#### Images / Videos

1.  [pexels](https://www.pexels.com/)
2.  [flaticon](https://www.flaticon.com/)

Changelog [\#back to top](#top)

------------------------------------------------------------------------
:::
:::

#### How to Upgrade [\#back to top](#top) {#line9_1 .sub-title}

If you have purchased an earlier version and want to upgrade your
website to the newwer version of this template, You can follow the
steps. In each update, we will keep a changelog or version history,
where we will keep the log of all changes made. We will list out the
Changes made, Features added and Pages modified. So it will be easier
for you to replace the existing.

If you have modified a file which has latest update, for example, CSS,
Open both page in a code editor and use a Comparison Sofware or an
Online Tool like [Diff Now](http://diffnow.com) to compare changes in
both files. Then you can manually copy paste the changed lines without
affecting your file. NOTE: We recommend that you keep a separate file
for new additions or changes if possible.

#### Version 1.0 [(27, feb 2022)]{.small} [\#back to top](#top) {#v1_0 .sub-title}

``` {.brush:html}
Initial Version
```

Rate it [\#back to top](#top)

------------------------------------------------------------------------

If you like the template, Please consider Rating it on Themeforest by
Visiting your Downloads Page : <http://themeforest.net/downloads> That
means a lot to me :)

![rate this template](images/upload/rate-template.png)

Support [\#back to top](#top)

------------------------------------------------------------------------

Please remember you have purchased a very affordable template and you
have not paid for a full-time web design agency. Occasionally we will
help with small tweaks, but these requests will be put on a lower
priority due to their nature. Please be patient, polite and respectful.
We will try to answer your questions as soon as possible

**Support for my items includes:**

1.  Responding to questions or problems regarding the item and its
    features
2.  Fixing bugs and reported issues
3.  Providing updates to ensure compatibility with new software versions

**Item support does not include:**

1.  Customization and installation services
2.  Support for third party software and plug-ins

**Before making a support request, please do\...**

1.  Make sure your question is a valid issue and not a customization
    request.
2.  Make sure you have read through the documentation and any related
    guides before asking support on how to accomplish a task.
3.  Try to use \"Google Search\" for common questions. Most of the
    times, which will help faster than the support.

[Contact Support](mailto:radwananik.ra@gmail.com){.btn .btn-danger

Thank you! [\#back to top](#top)

------------------------------------------------------------------------

Once again, Thank you so much for purchasing this template and being by
loyal customer. [Personal Email](mailto:radwananik.ra@gmail.com)

------------------------------------------------------------------------

Copyright ©

RadwanAnik. All rights reserved.

