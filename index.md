---

layout: default

style: |

    #Cover h2 {
        margin:65px 0 0;
        font-size:70px;
        text-align: center;
        }
    #Cover h3 {
        margin-top: 30px;
        position: static;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        font-style:italic;
        font-size:20px;
        }
    #Picture h2 {
        color:#FFF;
        }
    #SeeMore h2 {
        font-size:100px
        }
    #SeeMore img {
        width:0.72em;
        height:0.72em;
        }
    #live-demo h2,
    #live-demo .note,
    #by-home h2,
    #welcome-together h2 {
        background-color: rgba(0,0,0,.7);
        color: #fff;
        display: inline-block;
        padding: 0.5em;
        }
    .highlight{
        color: red;
    }

    .shout.with-picture img {
        max-height: 60%;
        margin: 0 auto;
        display: block;
    }
    .shout.with-picture h2 {
        font-size: 120px;
        -webkit-transform: translateY(75%);
        -moz-transform: translateY(75%);
        transform: translateY(75%);
        }
    .shout.medium h2{
       font-size: 70px;
    }
    .shout.medium.with-picture h2 {
        -webkit-transform: translateY(175%);
        -moz-transform: translateY(175%);
        transform: translateY(175%);
        }

    .slide, .slide.shout {
        background: #fff url(pictures/logo-tint.png) no-repeat 95% 90%;
        background-size: 150px;
        }
    .slide h2, .slide h3 {
        color: #444;
        }
    .slide h3 {
        width: 100%;
        font-size: 150%;
        text-align: center;
        position: absolute;
        left: 0;
        bottom: 30%;
        }
    .slide.with-subtitle h2 {
        -webkit-transform: translateY(-85%);
        -moz-transform: translateY(-85%);
        transform: translateY(-85%);
    }
    .left{
        text-algin: left;
    }
    .footnote {
        font-size: 75%;
        position: absolute;
        bottom: 0;
        }
---

# Secure Your Rails Application {#Cover}

<h3>The Basics</h3>

*xdite xdite@rocodev.com*

![](pictures/cover-roco.jpg)

## **Hi**

{:.shout.with-picture}
## xdite
![](pictures/xdite.png)

{:.shout.with-picture}
## Ruby on Rails
![](pictures/rails.jpg)


## Overview

* Security by default in Rails
* Common vulnerability of application design
* The solutions
* Write securit codes by default

{:.shout .medium .with-subtitle}
## Rails is (relatively) SAFE

### compare to other web frameworks

{:.shout .medium}
##Secure by default

{:.shout .medium}
##HTML Escape

{:.shout .medium}
##SQL Escape

{:.shout .medium}
##Authenticity Token

{:.shout .medium}
##Exception Page

{:.shout .medium}
##Password Encrypted 

{:.shout .medium}
##Sensitive data filtered from log

{:.shout .medium}
##Sanitize Filename 

{:.shout .medium}
##PHP way won’t work in Rails


{:.shout .medium}
## To hack into Rails

{:.shout .medium}
## follow the patterns


{:.shout }
## Common Mistakes

{:.shout .medium}
## #1. massive assignment

{:.shout .medium}
## #1.1. accepts_nested_attributes_for

{:.shout .medium}
## #1.2. role_ids

{:.shout .medium}
## #2. admin

{:.shout .medium}
## #3. bypass RESTful

{:.shout .medium}
## #4. bypass HTML Escape

{:.shout .medium}
## #5.bypass SQL escape

{:.shout .medium}
## #6. same secret token

{:.shout .medium}
## #7. except & only

{:.shout .medium}
## # 8. Remote Code Execution

## Thanks
{:.shout}


