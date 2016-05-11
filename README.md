# Features

## Customizable theme
The theme can be customized just by changing few variables in **_config.yml** file.

## Lightweight
Since the theme is based on default Jekyll theme, it is very lightweight. No JavaScript except analytics is used!

## Pre-installed features
Analytics and Disqus are pre-installed in this theme. You can set it up in **_config.yml** file. If left blank, these features will not load!


# Installation
Fork the ``master`` branch and delete ``gh-pages`` branch in it. This is important because ``gh-pages`` branch is used here only to host the blog. You should be using the master branch as the source and create a fresh ``gh-pages`` branch.

## How to delete old **gh-pages** branch?
After forking the repository, click on **branches**.

![delete gh-pages branch](/images/delete-github-branch.png)

Delete ``gh-pages`` branch.
![delete gh-pages branch](/images/delete-github-branch-2.png)

You have to create a new ``gh-pages`` branch using the master branch. Go back to the forked repository and create ``gh-pages`` branch.

![create gh-pages branch](/images/create-gh-pages-branch.JPG)

Now, go to settings and check the **Github Pages** section. You should see a URL where the blog is hosted.

This process will host the theme as a **Project Page**. You can also download the files for local development. 

Default theme will look like this

![webjeda purple jekyll theme](/images/webjeda-purple-jekyll-theme.png){: .border}

This theme is responsive.

![webjeda purple jekyll responsive theme](/images/webjeda-purple-jekyll-responsive-theme.png){: .border }
{: .text-center}


# Customization

## Theme
The theme provides a nice header that can be customized by changing colors in the **_config.yml** file. Use [**uiGradients**](http://uigradients.com/){: target="_blank" rel="nofollow"} to generate css gradients.

{% highlight yaml %}

#color scheme
color-1: '#155799'
color-2: '#159957'  

{% endhighlight %}

![webjeda sidebar theme](/images/webjeda-purple-jekyll-theme-2.png){: .border}

Remember, while developing locally, every change you make in **_config.yml** is applied only if you restart ``jekyll serve`` process.

## Font 
The default font is Source sans serif. It is hardcoded instead of downloading from Google fonts. This speeds up the theme a little bit. You can change this but I recommend not to.

## Logo
The **webjeda purple** logo is an SVG file. This can be removed and text can be used as the logo. Make these changes in the **header** file.

# Development
Make changes to the **master** branch and create a pull request. Do not use **gh-pages** branch as it is used to host the theme.


# License
MIT License