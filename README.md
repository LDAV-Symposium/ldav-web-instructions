# LDAV Web Instructions

This archive (and this readme file in particular) provides suggested
instructions for maintaining and updating the LDAV Symposium web pages. The
LDAV web pages are currently being hosted by GitHub pages, so modifying web
pages is done by updating files in the respective GitHub repositories.

Starting with the initial preparations for LDAV, beginning soon after the
previous year's symposium, the general procedure is as follows.

  1. [Create a new web page](#create-a-new-web-page)
  2. [Rotate in new page](#rotate-in-new-page)
  3. [Update page](#update-page)

## Create a new web page

To minimize the down time of the LDAV web pages, it is best practice to
create the web pages for a new year offline.

### Getting started

You are free to create the web page in whatever way you like, but using a
previous year's web page is probably the easiest way to start. Do not worry
about preserving the git history of the previous year. In fact, it is
better to start with a fresh git repository to save space. The git history
of previous web pages will be saved [when we rotate out the old
page](#rotate-in-new-page).

Also, when creating a new web page, do not worry about including the web
content from previous years. Again, this content will be archived [when we
rotate in the new page](#rotate-in-new-page).

### A brief primer to Jekyll

Many of the LDAV web pages were created with the [Jekyll] web page builder
tool. Here is a quick primer on how to get started with [Jekyll] if you
have not used it before.

Jekyll uses ruby, so first you need ruby installed on your system. Ruby
might already be installed on your system, but you might need a newer
version in order to be able to download the necessary packages. Generally,
you can use a package manager do the dirty work.

Next, if you don't have the `bundle` executable on your system, you need to
install bundler, which is done through the `gem` installer part of ruby.

``` sh
sudo gem install bundler
```

Once bundler is installed you can finally install Jekyll.

``` sh
sudo gem install jekyll
```

Typically, the first thing you need to do when you want to build a specific
repository is to make sure that you have all the packages and plugins
necessary. To update jupyter on local machine, be in this repositories root
directory and run:

``` sh
bundle install
```

You probably need to run this with root permissions (i.e. `sudo`).

Once you have done this, you should be able to run the Jekyll server, which
will build the html pages and start a simple web server.

``` sh
bundle exec jekyll serve
```

When you run the server, [Jekyll] will build the web pages in the `_site`
directory and start a lightweight web service that you can connect to with
your web browser.

## Rotate in new page

**Create**

## Update page

**Create**


[Jekyll]: https://jekyllrb.com/
