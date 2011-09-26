#detect.js
###provides the browser & os as a readable string.

## About

detect.js retrieves information about the user's browser using navigator.userAgent and navigator.platform. As these attributes can be changed easily, detect.js should be used to alter the behavior of a website for a specific platform. See feature detection.
## Usage

Add detect.js to your page:

    <script src="detect.js"></script>

Retrieve the browser, version, & os:
    
    console.log( window.ui.browser );
    console.log( window.ui.version );
    console.log( window.ui.os );
    
## window.ui

detect.js adds a 'ui' (short for user information) object to the window.

    window.ui = {
        browser : 'Firefox',
        version : '6.0.2',
        os : 'Mac OS X 10.7'
    }

## Which browsers are supported?
    
    Internet Explorer 6, 7, 8, 9, Mobile
    Firefox 3.6, 4, 5, 6, 7, Mobile
    Safari 3, 4, 5, Mobile
    Opera 9, 10, 11, Mini, Mobile 
    Chrome

## Which operating systems can be detected?

    Mac OS X
    Windows
    Linux
    Android
    iOS