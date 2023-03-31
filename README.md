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

## Multi-Blog Support<a href="#multi-blog-support">

So what is "***Multi-Blog Support?***"  

I wanted to be able to run seperate blogs in the same domain, so that I could have public blog posts, and private ones.  I did that by seperating posts by categories, using tags to search within that category.  Within ```_config.yml```, I changed the ```permalinks``` setting to not point to a category-based folder:

```
permalink: /:categories/:year/:month/:day/:title/
```

Then used the following <a href="https://shopify.github.io/liquid/basics/introduction/">liquid</a> tag to process only posts that have thier category set to *Blog*:

```
{% if post.categories contains 'Blog' %}
```

### Visit [this page](https://andresanz.com/about) for details about BootBox.

## Contact

[Contact Me](https://andresanz.com/contact)

[Project Page](https://github.com/andresanz/bootboxtemplate)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
