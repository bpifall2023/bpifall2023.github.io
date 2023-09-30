
#### A FEW WORDS ABOUT THE COURSE

<div style="text-align: justify;">Welcome to the <h1><b>Basic Physics I</b></h1>course! We're excited to have you on this academic journey. In this course, we will explore the fundamental principles that underlie the physical world around us. Whether you're new to physics or looking to strengthen your understanding, this course is designed to provide a solid foundation. We'll roughly cover mechanics, and our goal is to make physics accessible, engaging, and relevant to your everyday life. Feel free to reach out with questions, concerns, or simply to discuss your fascination with the wonders of the universe. Let's embark on this learning adventure together!</div>



### Remote Theme

Use `oinam-jekyll` as a [remote theme](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll) and you should be good to go. Add `remote_theme: oinam/oinam-jekyll` in the `_config.yml` file.

This is the preferred option. You get updates as soon as a new feature is added or bugs are fixed and updated on Github. You also get the latest versions.

### Template (Modify and Use)

Either fork the [repository](https://github.com/oinam/oinam-jekyll) or [Use this Template](https://github.com/oinam/oinam-jekyll/generate) from the repository on Github.

This option is suggested for Jekyll tinkerers and experts who are willing to update manually.

### Ruby Gem

The theme is also available as a [Ruby Gem](https://rubygems.org/gems/oinam-jekyll). This will be the least updated. Minor fixes and changes will <mark>NOT</mark> be reflected here quickly enough.

---
## Layouts

1. `home` layout where you can have content blurbs on the top and the last few recent posts.
2. `blog` layout that lists the titles of the posts along with the years as the headings.
3. `page` layout for pages.
4. `post` layout for posts.

### Configuration

The `_config.yml` has quite a few settings that are configurable. Removing the default Footer Credit and the Footer text are configurable. Choosing either Serif or Sans-Serif font-family, etc.

### Color

There are three basic color themes included -- `default`, [nord](https://www.nordtheme.com), and `vintage`. Treat them as samples for you to make your own. If you are tinkering with the code, you will find it as easy as just changing few color (HEX) values in the CSS. If you want to pick one of the three, pick a choice in `_config.yml`.

---
## Content

The [Styleguide]({{ site.baseurl | prepend: site.url }}/styleguide/) has examples and demos to treat images, videos, etc. with various layout and placement options.

---
## Development

Plain simple Jekyll and nothing else. Get Jekyll running on your local system and run this;

`$ bundle exec jekyll serve`

Or enable `drafts`, `future`, and serve it `incremental`;

`$ bundle exec jekyll serve --drafts --future --incremental`

---
## Contributing

You are welcome to contribute to the theme by sending in Pull Request with changes, edits, and fixes. Or, contribute by filing [Bugs and Issues](https://github.com/oinam/oinam-jekyll/issues).

There is a `server` that runs a local development server for development;

`$ ./server`

it is just a script that runs;

`$ bundle exec jekyll serve --config _config.yml,_config_dev.yml`

---
## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
