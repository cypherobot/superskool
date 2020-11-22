<p align="center">
  <img src="https://github.com/cypherobot/superskool/blob/master/logo.jpg" alt="Logo" width="150" height="150" />
</p>
<h1 align="center">SuperSkool by Anurag Deep</h1>
<p align="center">
<a href="https://david-dm.org/andreasbm/readme"><img alt="Dependencies" src="https://img.shields.io/david/andreasbm/readme.svg" height="20"/></a>
<a href="https://github.com/badges/shields"><img alt="Custom badge" src="https://img.shields.io/badge/custom-badge-f39f37.svg" height="20"/></a>
<a href="https://github.com/andreasbm/readme/graphs/commit-activity"><img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" height="20"/></a>
	</p>

<p align="center">
  <b>Developed Under Cyberlax domain for SuperSkool on Wordpress Plateform</b></br>
  <sub>beautifully coded and designed by Anurag with backend system Included<sub>
</p>

<br />


<p align="center">
  <img src="https://github.com/cypherobot/superskool/blob/master/front.png" alt="Demo" width="800" />
</p>

* **Simple**: Extremely simple to use - so simple that it almost feels like magic!
* **Powerful**: Customize almost everything - add your own templates and variables if you like.
* **Awesome**: when you will check it out, you feel the elagancy.


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#installation)

## ➤ Installation

just download wordpress from wordpress.org and insatll it in your local host or server.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#getting-started-quick)

## ➤ Getting Started (quick)

1. Copy these files by downloading zip or by clone it by git to your server directory for Xampp htdocs and for Linux server www/html folder.

2. change config.php file according to your database username and password, and creat database using phpmyadmin or command line.

3. after creation of database. import sql file that is given in our personal mail imbox. 

4. simply run the server and test the website in your browser.

### Different colored lines

If you want to change the color of the lines above headers you can change the `line` field in the `blueprint.json`. Here's an example if you want a dark line instead of the colored one.

```json
{
  "line": "dark"
}
```

The following is the dark variant of the line.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/dark.png)

Yeah! Dark mode on your `README.md` is awesome indeed. You have other options besides dark mode. Here's all the line styles you can choose from.

* "aqua" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png)
* "cloudy" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/cloudy.png)
* "colored" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)
* "cut" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/cut.png)
* "dark" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/dark.png)
* "fire" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/fire.png)
* "grass" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/grass.png)
* "rainbow" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
* "solar" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/solar.png)
* "vintage" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/vintage.png)
* "water" ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

If you want your own line design you can give the `line` field an url to an image instead. It is recommended that this image is 900px in width. If you prefer no line at all you can give the `line` field the string "none".

### Different formatted headings

If you want to change the prefix in front of the heading you can change the `headingPrefix` in the `blueprint.json` file. Just map the heading level to the desired prefix as shown below.

```json
{
  "headingPrefix": {
    "1": "➜ ",
    "2": "⭑ "
  }
}
```

If you want some inspiration for symbols you can put infront of the headings you can check out [this](https://unicodes.smpc.io/) website.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#featured-readmes)

## ➤ Featured README's

If you use this generator for one of your projects I would love to hear about it so I can feature it. Here's a list of some repositories using this generator for their README file.

* [lit-translate](https://github.com/andreasbm/lit-translate)
* [masonry-layout](https://github.com/andreasbm/masonry-layout)
* [focus-trap](https://github.com/andreasbm/focus-trap)
* [web-router](https://github.com/andreasbm/web-router)
* [web-config](https://github.com/andreasbm/web-config)
* [ts-lit-plugin](https://github.com/runem/ts-lit-plugin)
* [blob](https://github.com/andreasbm/blob)

As inspiration for the layout of the generated README files I initially found inspiration from [terkelg's brilliant repository called prompts](https://github.com/terkelg/prompts) - a prime example on how every README file should look! I therefore wanted to mention him here even though he doesn't use this README generator. If you want to see an example of a brilliant README file you should definitely check his repository out.


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#future-work)

## ➤ Future work

That's it for now! Lot's of exiting features a going to be added in the future. If you stumble upon an issue or have a feature request you are very welcome to open a Github issue or pull request. Have a great day!


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#faq)

## ➤ FAQ

### Can I see how my README file is going to look before I commit it?

Yes you definitely can! There are lots of tools out there for editing/previewing Github flavored markdown. I recommend using [https://stackedit.io/app](https://stackedit.io/app) to preview the final result since it is super lightweight and does it job well.

### How can I get involved?

Create an issue or pull-request. You are also very welcome to throw me a message at [@AndreasMehlsen](https://twitter.com/andreasmehlsen).

### I already have a large README file - I don't have time to rewrite everything!

No problem at all! Your first step can be to rename your `README.md` to `blueprint.md` and run `node_modules/.bin/readme generate`. Already then your README should now be well-formatted. Then you can slowly replace the contents when you have time. The low-hanging fruit would be to add the table of contents and license using respectively the `{{ template:toc }}` and `{{ template:license }}` templates.

### How can I support you?

There are lot's of ways to support me! I would be so happy if you gave this repository a star, tweeted about it or told your friends about this little corner of the Internet ❤️


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#contributors)

## ➤ Contributors
	

| [<img alt="Andreas Mehlsen" src="https://avatars1.githubusercontent.com/u/6267397?s=460&v=4" width="100">](https://twitter.com/andreasmehlsen) | [<img alt="You?" src="https://joeschmoe.io/api/v1/random" width="100">](https://github.com/andreasbm/readme/blob/master/CONTRIBUTING.md) |
|:--------------------------------------------------:|:--------------------------------------------------:|
| [Andreas Mehlsen](https://twitter.com/andreasmehlsen) | [You?](https://github.com/andreasbm/readme/blob/master/CONTRIBUTING.md) |
| 🔥                                               |                                                  |


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#license)

## ➤ License
	
Licensed under [MIT](https://opensource.org/licenses/MIT).