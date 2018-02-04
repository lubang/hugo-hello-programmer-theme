# Hugo Hello Programmer Theme

Hello Programmer is a simple blog theme.

![Hugo Hello Programmer Theme Screenshot](https://github.com/lubang/hugo-hello-programmer-theme/blob/master/images/screenshot.png)

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/lubang/hugo-hello-programmer-theme

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Config

Modify your configuration:

    $ vi config.toml

    baseurl = "your-site-address"
    title = "your-site-name"
    languageCode = "ko-KR"

    theme = "hello-programmer"

    paginate = 2

    disqusShortname = "XXXX"
    googleAnalytics = "UA-XXXXXXXX-X"

    [author]
        name = "your-name"
        email = "your-email"

Modify your theme image:

    static/images/logo@2X.png
    static/images/post-title-icon.png


## License

This theme is released under the [MIT License](//github.com/lubang/hugo-hello-programmer-theme/blob/master/LICENSE.md).
