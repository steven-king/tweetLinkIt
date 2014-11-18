tweetLinkIt
===========

Simple jQuery script to convert twitter tweet data to hyperlinked display.



1. Include Scripts:
```
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<script src="jquery.tweet-linkify.js"></script>
```
2. Apply Script:
```
    $('.tweet').tweetLinkify();
```
3. Note
When applying to a dynamic page the function needs to run after tweets are written to the DOM (HTML page).

Wrap in a function and call function  (pageComplete()) after the dynamic content is written.
 ```
 <script>
        
    function pageComplete(){
        $('.tweet').tweetLinkify();
    }
</script>
```
