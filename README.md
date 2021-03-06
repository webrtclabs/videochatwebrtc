# WebRTC video chat by webrtclabs
project site
 http://webrtclabs.github.io/videochatwebrtc
 demo site
 http://wlvideochat.appspot.com/
 
This plugin enables real-time streaming of video and/or audio between two web browsers(or peers).
<script data-gittip-username="webrtclabs"src="//gttp.co/v1.js"></script>

## Installation

- Download & unzip the source
- Move the source into your www directory
- Open the page http://yourserver/
- Enjoy!

## Use

### First, the HTML...

Place the following HTML code snippet within your <body> tag
  
    <!-- main container -->
    <div id="mainContainer" class="main-container">
    
        <!-- local video -->
        <video id="localVideo" class="local-video"></video>
    
        <!-- remote video -->
        <video id="remoteVideo" class="remote-video" autoplay></video>
    
        <!-- video status & room entry bar -->
        <div id="videoStatus" class="video-status"></div>
    
    </div>

### Then, the CSS...

Include the css within your head tag

    <link rel="stylesheet" href="css/fts-webrtc-styles.css">

And finally, the bloody brilliant piece that makes it all happen --the JavaScript!

This plugin enables real-time streaming of video between to browsers.

    <!-- JavaScript Ressources -->
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script src="js/jquery.fresh-tilled-soil-webrtc.js"></script>

    <!-- Plugin Initialization -->
    <script type="text/javascript">
        $(function() {
            $('#mainContainer').createVideoChat();
        });
    </script>

### Full Sample Demo Page (Putting it all Together)

This plugin enables real-time streaming of video between to browsers. S

    <!DOCTYPE html>
    <html>
    <head>
    <meta charset="UTF-8">
    <title>video chat by webrtclabs  | WebRTC jQuery Plug-in Demo</title>
    
    <!-- Stylesheet Resources -->
    <link rel="stylesheet" href="css/fts-webrtc-styles.css">
    
    </head>
    <body>
    
    <!-- main container -->
    <div id="mainContainer" class="main-container">
    
        <!-- local video -->
        <video id="localVideo" class="local-video"></video>
    
        <!-- remote video -->
        <video id="remoteVideo" class="remote-video" autoplay></video>
    
        <!-- video status & room entry bar -->
        <div id="videoStatus" class="video-status"></div>
    
    </div>
    
    <!-- JavaScript Ressources -->
    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
    <script src="js/jquery.fresh-tilled-soil-webrtc.js"></script>
    
    <!-- Plugin Initialization -->
    <script type="text/javascript">
        $(function() {
            $('#mainContainer').createVideoChat();
        });
    </script>
    
    </body>
    </html>
    
 ###sinal server for selfhosted servers
 
 http://webrtclabs.github.io/signalserver/

### Browser Support

Given the newness of WebRTC this jQuery plug-in has been created to support all major browsers that support the latest draft WebRTC specifications at the time of release. Below you will find a list & download links for the latest supported browsers:

- Chrome
- Chrome Beta for Android (for tablet & mobile phone support)
- FireFox
- Internet Explorer 10 (requires Google Chrome Frame plug-in)
- Chromium
- Chrome Canary
- FireFox Aurora
- FireFox Nightly
