# Universal Theme for Hugo

Universal is clean and stylish universal website template built with Bootstrap. It stands out with its clean design and elegant typography.

This Hugo theme is ported from [Bootstrapious](http://bootstrapious.com/p/universal-business-e-commerce-template).

![screenshot](https://raw.githubusercontent.com/devcows/hugo-universal-theme/master/images/screenshot.png)

## Features

* Fully responsive
* Customizable landing page
  * Carousel
  * Testimonials
  * Features
  * Customers
* Google search
* Disqus
* Google Analytics

## Installation

Go to the directory where you have your Hugo site and run:

```
$ mkdir themes
$ cd themes
$ git clone https://github.com/devcows/hugo-universal-theme universal
```

For more information read the official [setup guide of Hugo](https://gohugo.io/overview/installing/).

## Configuration

To take full advantage of the features in this theme you can add variables to your site config file, the following is the example config from the example site:

```toml
baseurl = "http://www.yourdomain.com/"
languageCode = "en-us"
theme = "universal"
title = "Universal"
# Enable comments by entering your Disqus shortname
disqusShortname = "devcows"
# Enable Google Analytics by entering your tracking code
googleAnalytics = ""
# Define the number of posts per page
paginate = 10

[params]
    author = "DevCows"

    # Since this template is static, the contact form uses www.formspree.io as a
    # proxy. The form makes a POST request to their servers to send the actual
    # email. Visitors can send up to a 1000 emails each month for free.
    #
    # What you need to do for the setup?
    #
    # - set your email address under 'email' below
    # - upload the generated site to your server
    # - send a dummy email yourself to confirm your account
    # - click the confirm link in the email from www.formspree.io
    # - you're done. Happy mailing!
    #
    # Enable the contact form by entering your Formspree.io email
    email = "info@devcows.com"

    about_us = "<p>Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.</p>"
    copyright = "Copyright (c) 2015 - 2016, YourCompany; all rights reserved."
    date_format = "2006-01-02"
    logo = "img/logo.png"
    address = """<p><strong>Universal Ltd.</strong>
        <br>13/25 New Avenue
        <br>Newtown upon River
        <br>45Y 73J
        <br>England
        <br>
        <strong>Great Britain</strong>
      </p>
      """

[[params.menu]]
    name = "Home"
    url  = "/"
    weight = 1

[[params.menu]]
    name = "Blog"
    url  = "/post"
    weight = 2

[[params.menu]]
    name = "FAQ"
    url  = "/faq"
    weight = 3

[[params.menu]]
    name = "Contact"
    url  = "/contact"
    weight = 4

[social]
    github = "devcows"

# Enable and disable widgets for the right sidebar
[params.widgets]
    categories = true
    tags = true
    search = true

[params.carousel]
    enable = true
    # All carousel items are defined in their own files. You can find example items
    # at 'exampleSite/data/carousel'.
    # For more informtion take a look at the README.

[params.features]
    enable = true
    # All features are defined in their own files. You can find example items
    # at 'exampleSite/data/features'.
    # For more informtion take a look at the README.

[params.testimonials]
    enable = true
    # All testimonials are defined in their own files. You can find example items
    # at 'exampleSite/data/testimonials'.
    # For more informtion take a look at the README.
    title = "Testimonials"
    subtitle = "We have worked with many clients and we always like to hear they come out from the cooperation happy and satisfied. Have a look what our clients said about us."

[params.see_more]
    enable = true
    icon = "fa fa-file-code-o"
    title = "Do you want to see more?"
    subtitle = "We have prepared for you more than 40 different HTML pages, including 5 variations of homepage."
    link_url = "#"
    link_text = "Check other homepages"

[params.clients]
    enable = true
    # All clients are defined in their own files. You can find example items
    # at 'exampleSite/data/clients'.
    # For more informtion take a look at the README.
    title = "Our Clients"
    subtitle = ""

[params.recent_posts]
    enable = true
    title = "From our blog"
    subtitle = "Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante. Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est. Mauris placerat eleifend leo."
```


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/devcows/hugo-universal-theme/issues) to let us know. Or make directly a [pull request](https://github.com/devcows/hugo-universal-theme/pulls).

## License

This port is released under the MIT License. Check the [original theme license](http://bootstrapious.com/p/universal-business-e-commerce-template) for additional licensing information.

## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [Bootstrapious](http://bootstrapious.com/) for creating this awesome theme.
