Direct Social Icons
===================
*Formerly known as Intent Social Icons*

A pure HTML & CSS implementation on allowing your end users to interact with social networks from your site without any need of loading in heavy JavaScript-based widgets.

## Installation 
#### Dependencies
* [Font Awesome](http://fortawesome.github.io/Font-Awesome/) 
* [Bower](http://bower.io/#install-bower) 

### Via Bower
Simply run:

```
bower install direct-social-buttons
```

### Via Manually

First download the `direct-social-buttons.css` in this repository and include it at the top of your page with the font awesome CDN link:

```html
<link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
<link rel="stylesheet" href="direct-social-buttons.css">
```
(Or where you have saved the `direct-social-buttons.css` file...)

Next view the demo.html page to find suitable social buttons and copy the code and you're done! :) 


## Examples & Usage
### Circle Icons
![Screenshot of Circle Direct Social Icons](http://i.imgur.com/xOxbDm3.png)
```html
<a href="//www.facebook.com/sharer/sharer.php?u=YOUR_URL" class="fa-stack fa-lg">
  <i class="fa fa-circle dsb-facebook fa-stack-2x"></i>
  <i class="fa fa-facebook fa-stack-1x dsb-white"></i>
</a>

<a href="//twitter.com/intent/tweet/?text=YOUR_TEXT&amp;url=YOUR_URL&amp;via=YOUR_TWITTER" class="fa-stack fa-lg">
  <i class="fa fa-circle dsb-twitter fa-stack-2x"></i>
  <i class="fa fa-twitter fa-stack-1x dsb-white"></i>
</a>

<a href="//plus.google.com/share?url=YOUR_URL" class="fa-stack fa-lg">
  <i class="fa fa-circle dsb-googleplus fa-stack-2x"></i>
  <i class="fa fa-google-plus fa-stack-1x dsb-white"></i>
</a>

<a href="javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;//assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());" class="fa-stack fa-lg">
  <i class="fa fa-circle dsb-pinterest fa-stack-2x"></i>
  <i class="fa fa-pinterest-p fa-stack-1x dsb-white"></i>
</a>

<a href="//www.linkedin.com/shareArticle?url=YOUR_URL&amp;title=YOUR%20TITLE&amp;summary=YOUR%20SUMMARY" class="fa-stack fa-lg">
   <i class="fa fa-circle dsb-linkedin fa-stack-2x"></i>
   <i class="fa fa-linkedin fa-stack-1x dsb-white"></i>
</a>
```
### Square Icons
![Screenshot of Square Direct Social Icons](http://i.imgur.com/nsRLSLp.png)
```html
a href="//www.facebook.com/sharer/sharer.php?u=YOUR_URL" class="fa-stack fa-lg">
  <i class="fa fa-square dsb-facebook fa-stack-2x"></i>
  <i class="fa fa-facebook fa-stack-1x dsb-white"></i>
</a>

<a href="//twitter.com/intent/tweet/?text=YOUR_TEXT&amp;url=YOUR_URL&amp;via=YOUR_TWITTER" class="fa-stack fa-lg">
  <i class="fa fa-square dsb-twitter fa-stack-2x"></i>
  <i class="fa fa-twitter fa-stack-1x dsb-white"></i>
</a>

<a href="//plus.google.com/share?url=YOUR_URL" class="fa-stack fa-lg">
  <i class="fa fa-square dsb-googleplus fa-stack-2x"></i>
  <i class="fa fa-google-plus fa-stack-1x dsb-white"></i>
</a>

<a href="javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;//assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());" class="fa-stack fa-lg">
  <i class="fa fa-square dsb-pinterest fa-stack-2x"></i>
  <i class="fa fa-pinterest-p fa-stack-1x dsb-white"></i>
</a>

<a href="//www.linkedin.com/shareArticle?url=YOUR_URL&amp;title=YOUR%20TITLE&amp;summary=YOUR%20SUMMARY" class="fa-stack fa-lg">
   <i class="fa fa-square dsb-linkedin fa-stack-2x"></i>
   <i class="fa fa-linkedin fa-stack-1x dsb-white"></i>
</a>
```

### Icons with Text
![Screenshot of Direct Social Icons with text label](http://i.imgur.com/yVAncsL.png)
```html
 
<a href="//www.facebook.com/sharer/sharer.php?u=YOUR_URL" class="dsb-btn dsb-facebook-bg dsb-white"><i class="fa fa-facebook"></i> Share</a>

<a href="//twitter.com/intent/tweet/?text=YOUR_TEXT&amp;url=YOUR_URL&amp;via=YOUR_TWITTER" class="dsb-btn dsb-twitter-bg dsb-white"><i class="fa fa-twitter"></i> Tweet</a>

<a href="//plus.google.com/share?url=YOUR_URL" class="dsb-btn dsb-googleplus-bg dsb-white"><i class="fa fa-google-plus"></i> Share</a>

<a href="javascript:void((function()%7Bvar%20e=document.createElement(&apos;script&apos;);e.setAttribute(&apos;type&apos;,&apos;text/javascript&apos;);e.setAttribute(&apos;charset&apos;,&apos;UTF-8&apos;);e.setAttribute(&apos;src&apos;,&apos;//assets.pinterest.com/js/pinmarklet.js?r=&apos;+Math.random()*99999999);document.body.appendChild(e)%7D)());" class="dsb-btn dsb-pinterest-bg dsb-white"><i class="fa fa-pinterest-p"></i> Pin It</a>

<a href="//www.linkedin.com/shareArticle?url=YOUR_URL&amp;title=YOUR%20TITLE&amp;summary=YOUR%20SUMMARY" class="dsb-btn dsb-linkedin-bg dsb-white"><i class="fa fa-linkedin"></i> Share</a>
```

## Credits
[Font Awesome](http://fortawesome.github.io/Font-Awesome/) - For the Social Network Logos

[Danny van Kooten](https://dannyvankooten.com/add-plain-html-social-sharing-links-posts/) - For the insight into social network intents

[Jeremy Mansfield](http://www.brandaiddesignco.com/insights/add-a-custom-pinterest-pin-it-button-to-your-website/) - For the insight into Pinterest functionality from URL

## License 
MIT
