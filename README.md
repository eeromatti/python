<br />
<div align="left">
  <h1>The highlights of my python projects</h1>
  <!--intro paragraph -->
  <p>In this repository I have collected some of the coolest python projects I have done during the coding studies:</p>
  <ul>
    <li>
      <a href="#robojump">RoboJump 3000 - a platform game made with Python's Pygame module</a>
    </li>
    <li>
      <a href=#radialfade">Radial fade filter for an image</a>
    </li>
    <li>
      <a href=#probabilistic">A probabilistic research on high blood pressure and coronary artery disease (linear and logistic regression)</a>  
    </li>  
  </ul>
</div>

<hr>

<h3 id="robojump">RoboJump 3000</h3>  

![image](https://github.com/user-attachments/assets/f7a3ef32-4f99-4c6f-8a43-d7c74293b82e)

<div>
  <p>RoboJump 3000 is a classic platformer game where the player controls a robot that needs to jump from one platform to another to stay in the game. The goal is to collect as many coins as possible. The difficulty increases incrementally due to the presence of ghosts (known as "mörkö") and the increasing speed of the platforms. This game project was a part of course called "Python programming MOOC" offered by Helsinki University. 
  </p>
  <p>The animation of the game was created with a Python module called <a href="https://en.wikipedia.org/wiki/Pygame">Pygame</a>. The logic in the code is briefly the following:
    <ul>
      <li>The platforms, coins, and ghosts are represented as groups of images, with their coordinates defined in a dictionary.</li>  
      <li>All elements (except for the robot) move downward at a predefined speed, which increases incrementally and makes it harder to stay in the game.</li>
      <li>A while loop updates the coordinates of these elements in each iteration. It also checks if the robot is moving, if it collects a coin or encounters a ghost, or if it falls out of the game.</li>
    </ul>
  </p>
</div>


<h3 id="radial_fade">Radial fade filter for an image</h3>

<img width="265" alt="image" src="https://github.com/user-attachments/assets/4a3036cf-b2b9-4ec5-a871-cd56c3f45633">
<br>
<div>
  <p>Radial fade filter makes a fading for a black&white (1-D)/color (3-D) image in radial direction. In other words, as we move away from the centre of the image, the pixels fade to black. The first image of the screen capture above is the original image, the second is the fading mask and the third one is the filtered image. This was a part of a programming course called "Data analysis with Python" offered by Helsinki University. 
  </p>
  <p>The filter was written in Python and the logic of the code is briefly as follows:
    <ul>
      <li>A mask array is created for the image that has a radial distance from the center of the image scaled to the range from 0 to 1 as the third dimension. The first and the second dimensions are the height and width of each pixel correspondingly.</li>  
      <li>The values in the mask array are inversed to make the values close to the center be close to 1 and the values further from the center close to 0.</li>
      <li>The third dimension of the mask array is converted to 3-D to be compatible with RGB images. Then the mask array is multiplied with the original image.</li>
    </ul>
  </p>
</div>







<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

There are many great README templates available on GitHub; however, I didn't find one that really suited my needs so I created this enhanced one. I want to create a README template so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should implement DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

Use the `BLANK_README.md` to get started.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![Next][Next.js]][Next-url]
* [![React][React.js]][React-url]
* [![Vue][Vue.js]][Vue-url]
* [![Angular][Angular.io]][Angular-url]
* [![Svelte][Svelte.dev]][Svelte-url]
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* [![JQuery][JQuery.com]][JQuery-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/othneildrew/Best-README-Template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=othneildrew/Best-README-Template" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 


## Intro

So you just decided to add a README to your project. You want to create an easy
to read and easy to navigate file.

The question is: What should you do next?

Should you create one from scratch? Find a silver bullet solution? Or is it
better to customize an already existing file?

I'm going to show you how to create a README that fits your project, is easy
to read and contains everyting you will ever need.

## Feature overview

*   [x] **Easy to read** like an article
*   [x] **Feature overview and Contents** for fast orientation
*   [ ] **Visuals** to keep users engaged

## Contents

*   [What is this?](#what-is-this)
*   [When should I use this?](#when-should-i-use-this)
*   [Getting started](#getting-started)
    *   [Requirements](#requirements)
    *   [Install](#install)
    *   [Usage](#usage)
*   [Here is where it's your turn](#here-is-where-its-your-turn)
*   [Don't forget anything](#dont-forget-anything)
    * [Used Technologies](#used-technologies)
    * [Testing](#testing)
    * [Logging](#logging)
*   [Contribute](#contribute)
*   [License](#license)
*   [Sources](#sources)
*   [Conclusion](#conclusion)

## What is this?

This project is an exhaustive README template that you can customize to your needs.
You can either add sections you like or remove sections you don't like. But you have
every time an example in front of you, from which you can derive from.

## Why should I use this?

There are many README templates out there so why this one? The two main reasons for this are
that they contain often too little content or they are not easy to read or navigate through.

## Getting Started

So how do you get this template to work for your project? It is easier than you think.

### Requirements

* Have a project ready where you can add a README
* Basic knowledge of [Markdown][about-markdown] (here is a [Cheatsheet][markdown-cheatsheet])

### Install

Use git to clone this repository into your computer.

```
git clone https://gitlab.com/kopino4-templates/readme-template
```

### Usage

Use the well known command to copy the template

```bash
# Copy the content
CTRL + C

# Pase into your project
CTRL + V
```

## Here is where it's your turn

Here starts the main content of your README. This is why you did it for in the first place.
To describe to future users of this project (including yourself) everything they need to know
to be able to use it and understand it.

Use visuals to help the reader understand better. An image, diagram, chart or code example says
more than thousand words

![Diagram](doc/diagram.jpg)

## Don't forget anything

Think hard about anything that is clear to you but might not be clear for others. Why are you
using this aproach or why did you pick this solution instead?

### Used technologies

For sure mention all the technologies you used. If the technologies age in time you don't forget
they are used and need to be replaced.

### Testing

No tests no sucess. You SHOULD have tests for every project, but do new users know how to run them?

### Logging

Logging is essential. How do you know something went wrong if the computer doesn't tell you? Logs
are the first place to search for bugs. Explain to everybody how you can customize it or used it
in the right way.

## Contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Sources

[react-markdown][react-markdown] - Project which served as an inspiration for this README

[Blog post templates][blog-post-templates] - Used to structure this template as an easy to read blog post

[About markdown][about-markdown] - Why should you use markdown?

[Markdown Cheat Sheet][markdown-cheatsheet] - Get a fast overview of the syntax

[//]: # "Source definitions"
[react-markdown]: https://github.com/remarkjs/react-markdown "React-markdown project"
[blog-post-templates]: https://backlinko.com/hub/content/blog-post-templates "Backlinko blog post templates"
[about-markdown]: https://www.markdownguide.org/getting-started/ "Introduction to markdown"
[markdown-cheatsheet]: https://www.markdownguide.org/cheat-sheet/ "Markdown Cheat Sheet"

## Conclusion

To summarize..

We have an exhaustive README template with many features. The README is easy to read and navigate like an article.
In our future projects we can use this template to get a great head start in creating a custom README.
