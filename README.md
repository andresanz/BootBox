<a name="readme-top"></a>

<div align="center">

<a href="https://github.com/andresanz/BootBox">
<img src="https://andresanz.com/assets/images/bootbox.png" alt="Logo">
</a>

<h3>&bull; The BootBox Jekyll Template &bull;</h3>

<a href="https://andresanz.com">View (self-serving) Demo</a>
&bull;
<a href="https://github.com/andresanz/BootBox/issues">Report Bug</a>
&bull;
<a href="https://github.com/andresanz/BootBox/discussions">Request Features</a>

</div>


## About BootBox
<div align="center" style="margin-top: 0px;">

![bootbox](https://andresanz.com/assets/images/BootBoxTemplatePrintScreen.png)

</div>

There are a lot of templates for Jekyll out there, but none of them seemed to do it for me.  I was looking for a simple template that included:
* NOT Wordpress ;)
* <a href="#multi-blog-support">Multi-blog support</a>
* local assets (as much as possible...)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

## Multi-Blog Support<a href="#multi-blog-support">

So what is "***Multi-Blog Support?***"  I wanted to be able to run seperate blogs in the same domain, so that I could have public blog posts, and private ones.  I did that by seperating posts by categories, using tags to search within that category.  Within ```_config.yml```, I changed the ```permalinks``` setting to not point to a category-based folder:

```
permalink: /:categories/:year/:month/:day/:title/
```

Then used the following <a href="https://shopify.github.io/liquid/basics/introduction/">liquid</a> tag to process only posts that have thier category set to *Blog*:

```
{% if post.categories contains 'Blog' %}
```


### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services.

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
```sh
git clone https://github.com/your_username_/Project-Name.git
```
3. Install NPM packages
```sh
npm install
```
4. Enter your API in `config.js`
```js
const API_KEY = 'ENTER YOUR API';
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Your Name - [@Nine14dotio](https://twitter.com/nine14dotio)

Project Link: [https://github.com/andresanz/bootboxtemplate](https://github.com/andresanz/bootboxtemplate)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
