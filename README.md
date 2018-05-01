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

After installing the **Hackatheme** theme successfully, we recommend you to take a look at the [exampleSite](https://github.com/open-network-infrastructure/hugo-hackatheme/tree/master/exampleSite) directory. You will find a working Hugo site configured with the Universal theme that you can use as a starting point for your site.

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
