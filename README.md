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
    DefaultContentLanguage = "kr"
    theme = "hugo-hello-programmer-theme"
    disqusShortname = "XXXX"
    googleAnalytics = "UA-XXXXXXXX-X"
    paginate = 7

    [author]
        name = "your-name"
        email = "your-email"

    [params]
        description = "desribe-your-site"

Modify images for your site:

    static/images/logo@.png (Left top logo image)
    static/images/thumbnail.png (OpenGraph tag for preview)

## Multilingual

Configure your language. Now support these languages. (updated 2019-06-09)

* kr (Korean, 한국어)
* en (English, a little bit stupid sentence :( Plz. Pull-request for this theme)

> You can pull request other languages or fix native sentence from exist language pack.

## References

Guide for Korean: https://blog.lulab.net/projects/2019-05-hugo-hello-programmer-theme-v2/

## License

This theme is released under the [MIT License](//github.com/lubang/hugo-hello-programmer-theme/blob/master/LICENSE.md).
