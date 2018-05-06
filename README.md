# Hackatheme for Hugo

> A multilingual theme for time-bounded co-creation events such as hackathons, with a meta twist.

**Hackatheme** is a Hugo theme designed to ease the organization of a hackathon and similar time-bounded events and publish it online.

It includes lots of open source delights, a sprinkle of stardust and plenty of chocolate chips 🍪.

It is also a **meta-project** in the sense that it includes documentation on how to replicate itself.

## Installation

Go to the directory where you have your Hugo site and run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/open-network-infrastructure/hugo-hackatheme

For more information read the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Configuration

After installing the **Hackatheme** theme successfully, we recommend you to take a look at the [exampleSite](https://github.com/open-network-infrastructure/hugo-hackatheme/tree/master/exampleSite) directory. You will find a working Hugo site configured with this theme that you can use as a starting point for your site.

First, let's take a look at the [config.toml](https://github.com/open-network-infrastructure/hugo-hackatheme/tree/master/exampleSite/config.toml). It will be useful to learn how to customize your site. Feel free to play around with the settings.

### Language

You can configure the language modifying the following key.

```toml
defaultContentLanguage = "en"
```

Available translations are in the `/i18n` directory.

### Google Analytics

You can optionally enable Google Analytics if you add your tracking code in the configuration.

```toml
googleAnalytics = "UA-XXXXX-X"
```


## TODO: Notes

- Add instructions to generate all icons (https://www.favicon-generator.org/)
- The name on the manifest.json needs to be changed
- Search and replace all occurrences of `Hackathon-in-a-box`
- Add slides.pdf to static downloads (as Page bundle?)
- Add site-verification instructions

<!-- ![screenshot](https://raw.githubusercontent.com/miguelsimoni/hugo-initio/master/images/tn.png)

## Installation
TODO: UPDATE

    $ cd /<your-hugo-site-directory>
    $ git submodule add https://github.com/miguelsimoni/hugo-initio.git themes/hugo-initio

More info: [hugo setup guide](https://gohugo.io/overview/installing/)

## Configuration

TODO: UPDATE

[Example Site](https://github.com/miguelsimoni/hugo-initio/tree/master/exampleSite)

[config.toml](https://github.com/miguelsimoni/hugo-initio/tree/master/exampleSite/config.toml)

### Sections

```toml
showSubheader = true
showServices = true
showRecentWorks = true
showDownload = true
showClients = true

footerEnableContact = true
footerEnableFollowme = true
footerEnableTextWidget = false
footerEnableFormWidget = false
```
### Social Networks Icons

You can add as many social networks as you want in the params.social array following this template:

```toml
[[params.social]]
  title = "facebook"
  url = "https://www.facebook.com/nickname"
  icon = "fa-facebook-square"
  footer = true
  sharethis = true
  network = "facebook"
```

See the whole configuration in the [config.toml](https://github.com/miguelsimoni/hugo-initio/tree/master/exampleSite/config.toml) file.

### Google Analytics

```toml
[params.google.analytics]
    trackerID = "GA-000000000-0"
```

Disable the Google Analytics by leaving `params.google.analytics.trackerID` empty.

### Almost there...

In order to see your site in action, you can run Hugo's built-in local server.

    $ hugo server

And open  [`http://localhost:1313/hugo-initio-site/`](http://localhost:1313/hugo-initio-site/) in the address bar of your browser.

## Deployment

TODO: Add details about travis

- [Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [More hosting and deployment options](https://gohugo.io/hosting-and-deployment/) -->

## Contributing

**Found a bug? Got an idea for a new feature?**

Let us know using the [issue tracker](https://github.com/open-network-infrastructure/hugo-hackatheme/issues) or send a pull request:

1. Fork it (<https://github.com/open-network-infrastructure/hugo-hackatheme>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request :D

## License

This project is licensed under the MIT License, see the [LICENSE](LICENSE) file for details.

## Credits

This theme is inspired, is based and/or relies on on several open source projects:

- [Bootstrap 4](https://getbootstrap.com/), licensed under the [MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE).
- [Material Design for Bootstrap](https://mdbootstrap.com/), licensed under the [MIT License](https://github.com/mdbootstrap/bootstrap-material-design/blob/master/license.txt).
- [Hugo-Initio theme](https://github.com/miguelsimoni/hugo-initio/) by [Miguel Simoni](https://miguelsimoni.xyz/), licensed under the [MIT License](https://github.com/miguelsimoni/hugo-initio/blob/master/LICENSE.md).
- [Initio template](http://www.gettemplate.com/info/initio/) by [Sergey Pozhilov, gettemplate.com](http://www.gettemplate.com/), licensed under the [CC-BY 3.0 License](http://creativecommons.org/licenses/by/3.0/).
- [Hugo](https://gohugo.io/), created by [Steve Francia](https://github.com/spf13).
