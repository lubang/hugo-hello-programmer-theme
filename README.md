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

    baseurl = "http://blog.lulab.net/"
    title = "LUBANG BLOG"
    languageCode = "ko-KR"

    theme = "hello-programmer"

    # Pagination
    paginate = 2

    [author]
        name = "your-name"
        email = "your-email"

    [Params]
        disqusShortname = "XXXX"
        googleAnalytics = "UA-XXXXXXXX-X"



## License

This theme is released under the [MIT License](//github.com/lubang/hugo-hello-programmer-theme/blob/master/LICENSE.md).
