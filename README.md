tweetLinkIt
===========

Simple jQuery script to convert twitter tweet data to hyperlinked display.



Include Scripts:
```
<script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>

<script src="tweetLinkIt.js"></script>
```
Apply Script:
```
    $('.tweet').tweetLinkify();
```
Note:
When applying to a dynamic page, for example a php call to twitter, the function needs to run after tweets are written to the DOM (HTML page).

Wrap in a function and call function  (pageComplete()) after the dynamic content is written.
 ```
 <script>
        
    function pageComplete(){
        $('.tweet').tweetLinkify();
    }
</script>

<?php
//run your twitter code and write to the page here.
// then echo this:
echo "<script>pageComplete();</script>;"
?>
```
