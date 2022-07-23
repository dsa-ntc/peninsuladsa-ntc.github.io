# To do
1. It is probably best to start a new Hugo project in a separate file and then copy files over as needed.
https://medium.com/featurepreneur/creating-a-website-using-hugo-and-github-pages-d30dc33d8f8a
https://chenhuijing.com/blog/migrating-from-jekyll-to-hugo/#%F0%9F%9A%B2

2. Then convert the Jekyll theme over to Hugo:
https://discourse.gohugo.io/t/how-to-port-jekyll-themes-to-hugo/3658
https://bwaycer.github.io/hugo_tutorial.hugo/tutorials/creating-a-new-theme/

3. Convert templates over to Hugo
https://gohugo.io/templates/introduction/

4. Port over SASS SCSS files
https://gohugo.io/hugo-pipes/scss-sass/


# Install (on Linux)
`sudo apt update` <br>
`sudo apt -y install hugo` <br>

Check to see if it works: <br>
`which hugo`


# File structure
How Hugo file structure differs from Jekyll.

## Hugo: https://gohugo.io/getting-started/directory-structure/
├── `archetypes` <br>
├── `config.toml` <br>
├── `content` <br>
├── `data` <br>
├── `layouts` <br>
├── `static` <br>
└── `themes` <br>

The following is a high-level overview of each of the directories with links to each of their respective sections within the Hugo docs.

[`archetypes`](https://gohugo.io/content-management/archetypes/)
> You can create new content files in Hugo using the `hugo new` command. By default, Hugo will create new content files with at least `date`, `title` (inferred from the file name), and `draft = true`. This saves time and promotes consistency for sites using multiple content types. You can create your own [archetypes](https://gohugo.io/content-management/archetypes/) with custom preconfigured front matter fields as well.

[`assets`](https://gohugo.io/hugo-pipes/introduction/#asset-directory)
> Stores all the files which need be processed by [Hugo Pipes](https://gohugo.io/hugo-pipes/). Only the files whose `.Permalink` or `.RelPermalink` are used will be published to the public directory. Note: `assets` directory is not created by default.

[`config`](https://gohugo.io/getting-started/configuration/)
> Hugo ships with a large number of [configuration directives](https://gohugo.io/getting-started/configuration/#all-configuration-settings). The [`config` directory](https://gohugo.io/getting-started/configuration/#configuration-directory) is where those directives are stored as JSON, YAML, or TOML files. Every root setting object can stand as its own file and structured by environments. Projects with minimal settings and no need for environment awareness can use a single `config.toml` file at its root.
> Many sites may need little to no configuration, but Hugo ships with a large number of [configuration directives](https://gohugo.io/getting-started/configuration/#all-configuration-settings) for more granular directions on how you want Hugo to build your website. Note: `config` directory is not created by default.

[`content`](https://gohugo.io/content-management/organization/)
> All content for your website will live inside this directory. Each top-level folder in Hugo is considered a [content section](https://gohugo.io/content-management/sections/). For example, if your site has three main sections — `blog`, `articles`, and `tutorials` — you will have three directories at `content/blog`, `content/articles`, and `content/tutorials`. Hugo uses sections to assign default [content types](https://gohugo.io/content-management/types/).

[`data`](https://gohugo.io/templates/data-templates/)
> This directory is used to store configuration files that can be used by Hugo when generating your website. You can write these files in YAML, JSON, or TOML format. In addition to the files you add to this folder, you can also create [data templates](https://gohugo.io/templates/data-templates/) that pull from dynamic content.

[`layouts`](https://gohugo.io/templates/)
> Stores templates in the form of `.html` files that specify how views of your content will be rendered into a static website. Templates include [list pages](https://gohugo.io/templates/single-page-templates/), [your homepage](https://gohugo.io/templates/homepage/), [taxonomy templates](https://gohugo.io/templates/taxonomy-templates/), [partials](https://gohugo.io/templates/partials/), [single page templates](https://gohugo.io/templates/single-page-templates/), and more.

[`static`](https://gohugo.io/content-management/static-files/)
> Stores all the static content: images, CSS, JavaScript, etc. When Hugo builds your site, all assets inside your `static` directory are copied over as-is. A good example of using the static folder is for [verifying site ownership on Google Search Console](https://support.google.com/analytics/answer/1142414?hl=en), where you want Hugo to copy over a complete HTML file without modifying its content.
From Hugo 0.31 you can have multiple static directories.

`resources`
> Caches some files to speed up generation. Can be also used by template authors to distribute built SASS files, so you don’t have to have the preprocessor installed. Note: `resources` directory is not created by default.


## Jekyll: https://jekyllrb.com/docs/structure/
. <br>
├── `\_config.yml` <br>
├── `\_data` <br>
│   └── `members.yml` <br>
├── `\_drafts` <br>
│   ├── `begin-with-the-crazy-ideas.md` <br>
│   └── `on-simplicity-in-technology.md` <br>
├── `\_includes` <br>
│   ├── `footer.html` <br>
│   └── `header.html` <br>
├── `\_layouts` <br>
│   ├── `default.html` <br>
│   └── `post.html` <br>
├── `\_posts` <br>
│   ├── `2007-10-29-why-every-programmer-should-play-nethack.md` <br>
│   └── `2009-04-26-barcamp-boston-4-roundup.md` <br>
├── `\_sass` <br>
│   ├── `\_base.scss` <br>
│   └── `\_layout.scss` <br>
├── `\_site` <br>
├── `.jekyll-cache` <br>
│   └── `Jekyll` <br>
│      &emsp; └── `Cache` <br>
│      &emsp; &emsp;     └── `[...]` <br>
├── `.jekyll-metadata` <br>
└── `index.html` # can also be an 'index.md' with valid front matter


`\_config.yml`
> Stores [configuration](https://jekyllrb.com/docs/configuration/) data. Many of these options can be specified from the command line executable but it’s easier to specify them here so you don’t have to remember them. 

`\_drafts`
> Drafts are unpublished posts. The format of these files is without a date: `title.MARKUP`. Learn how to [work with drafts](https://jekyllrb.com/docs/posts/#drafts). 

`\_includes`
> These are the partials that can be mixed and matched by your layouts and posts to facilitate reuse. The liquid tag `{% include file.ext %}` can be used to include the partial in `\_includes/file.ext`. 

`\_layouts`
> These are the templates that wrap posts. Layouts are chosen on a post-by-post basis in the [front matter](https://jekyllrb.com/docs/front-matter/), which is described in the next section. The liquid tag `{{ content }}` is used to inject content into the web page. 

`\_posts`
> Your dynamic content, so to speak. The naming convention of these files is important, and must follow the format: `YEAR-MONTH-DAY-title.MARKUP`. The [permalinks](https://jekyllrb.com/docs/permalinks/) can be customized for each post, but the date and markup language are determined solely by the file name. 

`\_data`
> Well-formatted site data should be placed here. The Jekyll engine will autoload all data files (using either the .`yml`, `.yaml`, .`json`, `.csv` or `.tsv` formats and extensions) in this directory, and they will be accessible via `site.data`. If there's a file `members.yml` under the directory, then you can access contents of the file through `site.data.members`. 

`\_sass`
> These are sass partials that can be imported into your `main.scss` which will then be processed into a single stylesheet `main.css` that defines the styles to be used by your site. Learn [how to work with assets](https://jekyllrb.com/docs/assets/). 

`\_site`
> This is where the generated site will be placed (by default) once Jekyll is done transforming it. It’s probably a good idea to add this to your `.gitignore` file. 

`.jekyll-cache`
> Keeps a copy of the generated pages and markup (e.g.: markdown) for faster serving. Created when using e.g.: `jekyll serve`. Can be disabled with an [option and/or flag](https://jekyllrb.com/docs/configuration/options/). This directory will not be included in the generated site. It’s probably a good idea to add this to your `.gitignore` file. 

`.jekyll-metadata`
> This helps Jekyll keep track of which files have not been modified since the site was last built, and which files will need to be regenerated on the next build. Only created when using [incremental regeneration](https://jekyllrb.com/docs/configuration/incremental-regeneration/) (e.g.: with `jekyll serve -I`). This file will not be included in the generated site. It’s probably a good idea to add this to your `.gitignore` file. 
index.html or index.md and other HTML, Markdown files <br>
> Provided that the file has a [front matter](https://jekyllrb.com/docs/front-matter/) section, it will be transformed by Jekyll. The same will happen for any `.html`, `.markdown`, `.md`, or `.textile` file in your site’s root directory or directories not listed above. 

Other Files/Folders
> Except for the special cases listed above, every other directory and file — such as `css` and `images` folders, `favicon.ico` files, and so forth — will be copied verbatim to the generated site. There are plenty of [sites already using Jekyll](https://jekyllrb.com/showcase/) if you’re curious to see how they’re laid out. 
