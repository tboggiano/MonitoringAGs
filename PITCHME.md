## Monitoring Availability Groups

### By Tracy Boggiano

![ImageLargeLogo](assets/image/largelogo.jpg)

---
## Welcome to SQLSaturday Denver!
![ImageWelcome](assets/image/welcome.jpg)

---
## About Me

![ImageAvatar](assets/image/avatar.png)<br>
Tracy Boggiano<br>
Database Superhero<br>
Broadvine

---

## About Me

**SQL Experience**
* 19+ years experience on SQL Server going back to 6.5
* MCDBA SQL 7 certification, most recently MCSE on 2012

**PASS Involvement**
* Idera Ace 2018 and Idera Super Star 2018
* Co-leader of SIG Advanced DBA of TriPass In Raleigh
* Leading getting Linux content in the existing Virtual Groups

---
## About Me

**Volunteer Work**
* Founder of [WeSpeakLinux.com](http://WeSpeakLinux.com)
* Member of [SpeakingMentors.com](http://SpeakingMentors.com)
* Volunteer with abused and neglected foster children through the [NC Guardian ad Litem](http://volunteerforgal.org) also known as [CASA](http://casaforchildren.org) nationwide for 15+ years

---?code=sample/go/server.go&lang=golang&title=Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---

@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

## Template Help

- [Code Presenting](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Repo Source](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides), [Static Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides), [GIST](https://github.com/gitpitch/gitpitch/wiki/GIST-Slides) 
- [Custom CSS Styling](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Slideshow Background Image](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [Slide-specific Background Images](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting) [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents) [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

## Go GitPitch Pro!

<br>
<div class="left">
    <i class="fa fa-user-secret fa-5x" aria-hidden="true"> </i><br>
    <a href="https://gitpitch.com/pro-features" class="pro-link">
    More details here.</a>
</div>
<div class="right">
    <ul>
        <li>Private Repos</li>
        <li>Private URLs</li>
        <li>Password-Protection</li>
        <li>Image Opacity</li>
        <li>SVG Image Support</li>
    </ul>
</div>

---

### Questions?

<br>

@fa[twitter](@TracyBoggiano)

@fa[github](github.com/tboggiano)

@fa[envelope](tracy@tracyboggiano.com)

@fa[wordpress](databasesuperhero.com)