---

layout: default

style: |

    #Cover h2 {
        margin:65px 0 0;
        color:#FFF;
        text-align:center;
        font-size:70px;
        }
    #Cover p {
        margin:10px 0 0;
        text-align:center;
        color:#FFF;
        font-style:italic;
        font-size:20px;
        }
        #Cover p a {
            color:#FFF;
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
    .highlight{
        color: red;
    }

    .shout.medium h2{
       font-size: 70px; 
    }
    .left{
        text-algin: left;
    }
---

# Why Frontend should using Rails? {#Cover}

*Brought you by [xdite](http://rocodev.com/)*

![](pictures/cover.jpg)
<!-- photo by John Carey, fiftyfootshadows.net -->

## **Hi**

## **xdite**

## **Ruby on Rails**

## **Fulltime Business Developer**

## **兩個重點**

// 本場只有兩個重點：

## Best Practicss for <br>Speeding Up Your Website
{:.shout .medium}

## Asset Pipeline
{:.shout .medium}

## 在 JSDC 講 Rails ?
{:.shout .medium}

// 相信很多人對我挑這個題目來講，一定覺得很奇怪。

## 明明 node.js 比較快
{:.shout .medium}

## 速度比較表

<table style="border:1px #000000 solid; padding:2px; text-align:center;" width="90%">
    <tr> 
        <td width="37%"> Web 框架 </td>
        <td width="35%"> 併發模型 </td>
        <td width="45%"> 531 req / s </td>
    </tr>

    <tr> 
        <td> Rails  </td>
        <td> Multiple Process </td>
        <td> 531 req / s  </td>
    </tr>

    <tr> 
        <td> Sinatra  </td>
        <td> Multiple Process </td>
        <td> 576 req / s  </td>
    </tr>

    <tr> 
        <td> Sinatra::Synchrony </td>
        <td> Fibers </td>
        <td> 1692 req / s  </td>
    </tr>

    <tr> 
        <td> Goliath </td>
        <td> Fibers </td>
        <td> 1924 req / s  </td>
    </tr>

    <tr> 
        <td> Cramp </td>
        <td> Event IO  </td>
        <td> 3516 req / s  </td>
    </tr>
    <tr> 
        <td> Node.js </td>
        <td> Event IO </td>
        <td class="highlight"> 3100 req / s </td>
    </tr>
</table>

## node.js 比 Rails 快了 <span class="highlight">6</span> 倍
{:.shout .medium}

## 那...
{:.shout .medium}

// 那...為什麼還要講這個題目？

## 現場調查
{:.shout}

## Best Practicss for <br>Speeding Up Your Website
{:.shout .medium}

## 速度比較表

<table style="border:1px #000000 solid; padding:2px; text-align:center;" width="90%">
    <tr> 
        <td width="37%"> Web 框架 </td>
        <td width="35%"> 併發模型 </td>
        <td width="45%"> 531 req / s </td>
    </tr>

    <tr> 
        <td> Rails  </td>
        <td> Multiple Process </td>
        <td> 531 req / s  </td>
    </tr>

    <tr> 
        <td> Sinatra  </td>
        <td> Multiple Process </td>
        <td> 576 req / s  </td>
    </tr>

    <tr> 
        <td> Sinatra::Synchrony </td>
        <td> Fibers </td>
        <td> 1692 req / s  </td>
    </tr>

    <tr> 
        <td> Goliath </td>
        <td> Fibers </td>
        <td> 1924 req / s  </td>
    </tr>

    <tr> 
        <td> Cramp </td>
        <td> Event IO  </td>
        <td> 3516 req / s  </td>
    </tr>
    <tr> 
        <td> Node.js </td>
        <td> Event IO </td>
        <td class="highlight"> 3100 req / s </td>
    </tr>
</table>

## 這張表講的是 <br> <br>「網頁產生速度」
{:.shout .medium}

## 回到正題
{:.shout}

## Scaling Websites
{:.shout}

## Priciples

* Front-end speed
* SQL Query speed
* Method speed
* Programing Language speed


##  Front-end performance
{:.shout .medium}

##  7s -> 1s
{:.shout}

##  SQL Query Performance
{:.shout .medium}

##  500ms -> 50ms
{:.shout}

##  Method Performance
{:.shout .medium}

##  50ms -> 10ms
{:.shout}

##  Programming Language Performance
{:.shout .medium}

##  5ms -> 2ms
{:.shout}


##  Webpage 產生速度 = <br><br> SQL Query speed + <br> <br>Method speed + <br><br> Programing Language speed 
{:.shout .medium .left}


## 比較語言和框架本身的速度沒什麼意義

* node.js V.S. Rails
* Rails V.S. Sinatra
* Rails V.S. PHP
* ....

## 省下來的時間 ：<br> <br> (7s - 1s ) > ( 550ms - 62ms)
{:.shout .medium}

##  What can Rails do ?
{:.shout .medium}

## Speed Frontend Performance <span class="highlight">by default</span>
{:.shout .medium}

## Easy to imeplement parallel download

The `HTTP/1.1` specification suggests that browsers download **no more than two components** in parallel per hostname. If you serve your images from `multiple hostnames`, you can get more than two downloads to occur in parallel. 

## Easy to apply CDN

* TODO

## Easy to invalid CDN cache

* TODO

## Easy to minimal HTTP Request

* TODO

## Auto CSS Sprite

* TODO

## Auto Gzip

* TODO

## Auto minify asset

* TODO

## Auto ETag

* TODO

## 第一天就內建
{:.shout}


## That's why you should use Rails
{:.shout .medium}


## Rails 還能作什麼？
{:.shout .medium}

## Package Management
{:.shout .medium}

## Gemfile

    gem "jquery"
    gem "font-awesome"
    gem "tinymce-rails"
    gem "bootstrap-rails"
    gem "backbone-on-rails"


## Bootstrap Hack (1)

## Bootstrap Hack (2)

## Backbone on Rails (1)

## Backbone on Rails (2)



## And there's more in Rails 4
{:.shout .medium}


## Live Streaming
{:.shout}

## (DEMO)
{:.shout}

## Turbolinks
{:.shout}

## (DEMO)
{:.shout}


## 總結
{:.shout}

## 歡迎一起學習 Rails！
{:.shout .medium}

## 如果你想要學 Rails 的話

* http://blog.xdite.net
* http://blog.rocodev.com
* http://www.meetup.com/taipei-rails-meetup/

## Thanks
{:.shout}


## blah

Lorem ipsum dolor sit amet, consectetur [adipisicing](#all-kind-of-lists) elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, *quis nostrud* exercitation ullamco laboris **nisi ut aliquip** ex ea commodo consequat. Duis aute irure <i>dolor</i> in reprehenderit in voluptate velit esse cillum <b>dolore</b> eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in `<culpa>` qui officia deserunt mollit anim id est laborum.

## All Kind of Lists

1. Simple lists are marked with bullets
2. Ordered lists begin with a number
3. You can even nest lists one inside another
    - Or mix their types
    - But do not go too far
    - Otherwise audience will be bored
4. Look, seven rows exactly!

{:.note}
Shower ['ʃəuə] noun. A person or thing that shows.

## Serious Citations

<figure markdown="1">

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia.

<figcaption>Marcus Tullius Cicero</figcaption>
</figure>

## Code Samples

    <!DOCTYPE html>
    <html lang="en">
    <mark><head></mark> <mark class="comment"><!--Comment--></mark>
        <title>Shower</title>
        <meta charset="<mark class="important">UTF-8</mark>">
        <link rel="stylesheet" href="screen.css">
    <mark></head></mark>

## Pictures
{:.cover #Picture}

![](pictures/picture.jpg)
<!-- photo by John Carey, fiftyfootshadows.net -->

## **You can even shout this way**

## Inner Navigation

1. Lets you reveal list items one by one
2. …To keep some key points
3. …In secret from audience
4. …But it will work only once
5. …Nobody wants to see the same joke twice
6. xxx

## ![](http://shwr.me/pictures/logo.svg) [See more on GitHub](https://github.com/shower/shower/)
{:.shout #SeeMore}
