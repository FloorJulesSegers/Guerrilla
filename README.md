
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
* [My website](#my-website)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

## About The Project
I created and deployed a one-pager in 8 hours. I gathered content from a café that has no website, only a Facebook page. 

![TGC](https://user-images.githubusercontent.com/49682756/57457503-f478bb00-726f-11e9-9cd5-2930cfafa599.png)

![TGC2](https://user-images.githubusercontent.com/49682756/57457507-f5a9e800-726f-11e9-9414-c352e99eb76c.png)

![TGC4](https://user-images.githubusercontent.com/49682756/57457512-f6db1500-726f-11e9-90b1-d909ae2674ad.png)

##Built with
[Bootstrap](https://getbootstrap.com)

## Getting started
I used a free bootstrap template from [Start Bootstrap](https://startbootstrap.com/templates/.).

![startbootstrap](https://user-images.githubusercontent.com/49682756/57458335-73222800-7271-11e9-9eaa-1aa9f328f9f2.png)

The template already has:
* A simple navbar
* Two full width images
* 2 sections that interrupt the images
* A footer

## My website
I made some changes to the navbar: 
* I made the navbar transparent:`.navbar{background-color: transparent;}`
* I inserted a search bar with Bootstrap `<form class="form-inline"`
* Image:`.navbar-brand`

Instead of an image in the header:
* Two different headings: `h1`& `h2`
* Bigger image with: `header > h1{ padding-top: 200px}`& `header > h2{ padding-bottom: 200px}` 

Inserted 3 cards in the section class:
1. "Over ons" with text and an info button
2. "Foto's" with a thumbnail image: `<img src="..." alt="..." class="img-thumbnail">`
3. "Evenementen":

 `<time datetime="2019-05-07">
 
  <span class="day">7</span>
  
  <span class="month">Mei</span>
  
  <span class="year">2019</span>
  
   <span class="time">20:00</span>  
   
  </time></p>`

In the last section I inserted Google Maps:

`<div class="map-responsive">

  <iframe src="..." width="600" height="450" frameborder="1px" style="border:1px" allowfullscreen></iframe></div>`


## Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-full-width-pics/blob/gh-pages/LICENSE) license.
