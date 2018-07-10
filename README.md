# hyde-hyde

__`hyde-hyde`__ is a [Hugo](https://gohugo.io)'s theme derived from @spf13's [Hyde](https://github.com/spf13/hyde.git) which is in turn ported from @mdo Jekyll's [Hyde](https://github.com/poole/hyde). 

## Notable Changes
* Color tones and layouts are inspired by [Nate Finch's blog](https://npf.io)
* Restructuring/modularising the layouts (see [`layouts/_default/baseof.html`](https://github.com/htr3n/hyde-hyde/blob/master/layouts/_default/baseof.html), [`layouts/_default/single.html`](https://github.com/htr3n/hyde-hyde/blob/master/layouts/_default/single.html), [`layouts/_default/list.html`](https://github.com/htr3n/hyde-hyde/blob/master/layouts/_default/list.html) and [`layouts/partials`](https://github.com/htr3n/hyde-hyde/blob/master/layouts/partials/))
* Using [highlight.js](https://highlightjs.org) for code highlighting
* Using [Font-Awesome 5](https://fontawesome.com)'s icons
* Using main font [Fira-Sans](https://fonts.google.com/specimen/Fira+Sans) + fixed width font [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono)
* Adding [GraphComment](https://graphcomment.com) for replacing the built-in [Disqus](https://disqus.com)

A real site in action can be found [here](https://htr3n.github.io) with its [WIP source](https://github.com/htr3n/htr3n-blog) for reference.

Some screenshots:

![hyde-hyde main screen](https://github.com/htr3n/hyde-hyde/blob/master/images/main.png)

![A post in hyde-hyde](https://github.com/htr3n/hyde-hyde/blob/master/images/post.png)

## Installation

`hyde-hyde` can be easily installed as many other Hugo's themes:

```sh
$ cd HUGO_SITE
# then clone hyde-hyde
$ git clone https://github.com/htr3n/hyde-hyde.git themes/hyde-hyde
# or add hyde-hyde as a submodule
$ git submodule add https://github.com/htr3n/hyde-hyde.git themes/hyde-hyde
```

Then choose `hyde-hyde` as the main theme

* `config.toml` 

```tomp
theme = "hyde-hyde"
```

* `config.yaml`

```yaml
theme : "hyde-hyde"
```

That's all. You can render your site using `hugo` and see the template in action.

## Options

* `hyde-hyde` essentially inherits [all options](https://github.com/spf13/hyde#options) from Hyde.

## Customisations

* Most of the newly added customisations are in the file [`hyde-hyde/static/css/hyde-hyde.css`](https://github.com/htr3n/hyde-hyde/blob/master/static/css/hyde-hyde.css).
* The layouts for a single post or a list/table of content in [`hyde-hyde/layouts`](https://github.com/htr3n/hyde-hyde/blob/master/layouts) are modularised and can be changed easily.

## Author(s)

### Original Developed by Mark Otto

- <https://github.com/mdo>
- <https://twitter.com/mdo>

### Hugo's Hyde Ported by Steve Francia
- <https://github.com/spf13>
- <https://twitter.com/spf13>

### Color Theme Inspired By

* [Nate Finch's blog](https://npf.io)

## License

Open sourced under the [MIT license](LICENSE.md).
