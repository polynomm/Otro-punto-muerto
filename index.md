---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
last_modified_date: 2020-04-27T17:54:08+0000
---

<link rel="stylesheet" href="{{ '/assets/css/just-the-docs-default.css' | absolute_url }}">

# Focus on writing good documentation<i class="jpa-anim-rel-smiling_face_with_sunglasses jpa-1em"></i><i class="jpa-heart_eyes jpa-1em"></i>
{: .fs-9 }

\$\$x^2\$\$
{: .deg-sitio .deg-sitio-texto .grid}

<span>\\(x^2\\)</span>{: .deg-sitio .deg-sitio-texto} Madre de todos los cuadrados.
Just the Docs  gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .deg-numeros .deg-numeros-fondo .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .deg-numeros .deg-numeros-texto .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### Dependencies

Just the Docs is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).
Just the Docs is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).

<script type="text/javascript">
				function perspective(p){
					updateHelp(p);
					ggbApplet.setPerspective(p);
				}
                var parameters = {
                        "id":"ggbApplet",
                        "appName":"geometry",
                        "width":800,
                        "height":600,
                        "showToolBar":true,
                        "borderColor":null,
                        "showMenuBar":true,
                        "allowStyleBar":true,
                        "showAlgebraInput":true,
                        "enableLabelDrags":false,
                        "enableShiftDragZoom":true,
                        "capturingThreshold":null,
                        "showToolBarHelp":false,
                        "errorDialogsActive":true,
                        "showTutorialLink":true,
                        "showLogging":true,
                        "useBrowserForJS":false,
                        "autoHeight":true,
                        "scaleContainerClass":"geo-ajuste50",
                        "allowUpscale":false
                        };
                var applet = new GGBApplet(parameters, '5.0', 'applet_container');
               /*  when used with Math Apps Bundle, uncomment this:*/
                /*applet.setHTML5Codebase('GeoGebra/HTML5/5.0/web3d/');*/

                window.onload = function() { applet.inject('applet_container'); }
  </script>

  <!--Encerrar dentro de un div el applet soluciona el problema de impresión en escritorio (el applet se mueve de su posición) En teléfonos cambia sigue el problem.-->
<div class="geo-div"><div class="geo-ajuste50"><div id="applet_container" class="geo-print50"></div></div></div>

### Quick start: Use as a GitHub Pages remote theme

1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

\$\$x^2\$\$
{: .deg-sitio .deg-sitio-texto .math-display}

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/pmarsceill/just-the-docs/tree/master/CODE_OF_CONDUCT.md) on our GitHub repository.

<script>
  jtd.setTheme('degVerde')
  </script>