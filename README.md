# DSA Chapter In a Box Website Runbook
This repo provides both a theme for Chapters and Organizing Committees of the Democratic Socialists of America (refered herein as "Chapters" for shorthand), as well as a runbook to get this up and running for any Chapter that wants it. The theme is based on the [Lone Wolf Theme](https://github.com/manid2/lone-wolf-theme) for Jekyll.

Smaller Chapters, or Chapters without a dedicated internal Tech committee, may lack a web presence outside of Corporate owned Social Media. To assist with this, the National Tech Committee (NTC) has created this runbook to help quickly get chapter webpages up and running with DSA branding. 

Free web hosting may be acquired from Gitlab, an open source version control website for software developers, but can be used solely for hosting static webpages or blogs. In this runbook, we will be setting up a webpage using Jekyll, a static webpage generator on a Gitlab instance, however you may use this to self-host if your chapter has a webserver. 

References: 
Example assets can be found here: https://gitlab.com/cmahns/cmahns.gitlab.io

Example webpage can be viewed here: https://cmahns.gitlab.io/

Jekyll documentation can be found here: https://jekyllrb.com/docs

The Lone Wolf Theme Example page can be found here: https://manid2.github.io/lone-wolf-theme/

## Expectations and Limitations
This project's function is for the NTC to provide the means for smaller DSA Chapters to establish a Jekyll based website quickly and at no cost. The ownership (e.g. updates to content, updates to theme, customization) is expected to fall on the individual Chapter with minimal support from the NTC outside of onboarding. There is no requirement the website must be hosted on GitLab Pages, use this Jekyll theme, or use this project. 

Jekyll, the base code for this website and this project, is a static website generator, meaning some "dynamic" functionality like a comments section, dynamic chapter calendars for tracking events, or some embedded media, are not supported. The [Jekyll documentation](https://jekyllrb.com/docs) can help further explain what will and won't work if implemented on your website. GitLab has a [comparison between static and dynamic](https://about.gitlab.com/blog/2016/06/03/ssg-overview-gitlab-pages-part-1-dynamic-x-static/) webpages which will further explain the difference. 

## Installation
This document will be around using the hosted gitlab instance as self-hosting this same website is out of scope of this document. This document will also assume a small amount of familiarity with `git` for version control and the Markdown markup language for creating pages on the website. 

You will also need a GitLab account and a GitLab project for your chapter. While GitLab pages can be created both on personal and group accounts, it's recommended to make this a Chapter based account to provide additional access if needed. 

1. Visit [this page](https://gitlab.com/groups/new) to create a new Group. It's recommended to keep this either the full name or an abbreviation of your chapter to help reduce taking an already used name.
2. After the group is created, create a new Project using the **New Project** button
3. Make the title name `$GROUPNAME.gitlab.io` where $GROUPNAME is the Group name you set in Step 1
4. Use the repo files here, to begin creating the framework for your new Chapter's website. You can do this by cloning this repo in to your new Project's repo, or downloading the .zip of the source code here and upload it to the Project's repo

GitLab will begin compiling and deploying the new Jekyll blog each update to the website's codebase through the integrated Continuous Integration provided by them, so you will not need to push changes to your website after you create them!

More details can be found in [GitLab's instructions](https://docs.gitlab.com/ee/user/project/pages/#gitlab-pages)

##  Updating Website
All pages for this new website are contained in the `_pages` directory. There are several pages created as examples, here are the main ones:

`404.md` -- Example 404 page which Jekyll will direct any page to if it doesn't otherwise exist, you can customize this further to your chapter's content. 

`about.md` -- A quick about summary of your chapter, why the chapter was formed, how it ties in to the history of your area. 

`blog.md` -- Placeholder for a chapter blog or statements page (which can be renamed and updated as per your chapter's preference). An example of a blog post / chapter statement (contained in `_posts/2021-09-20-ice-statement.md`) is provided to further illustrate how this page can be used to automatically group statements/blogs

`calendar.md` -- A page where you can embed or provide a calendar around events and actions your Chapter is participating in

`get-involved.md` -- A page where you can provide additional instructions for potential memebers to join your Chapter.

## Customizing Website
A handful of files need to be updated to better customize your chapter's webpage. 

`_data/nav.yml` -- This contains both the header and footer bars on the webpage, and will be added to every post or page made in the above section. Example values are provided from DSA National.  

`_sass/bootswatch/dist/united/_variables.scss` -- This controls the variables for colors and font for the webpage, currently defaults are kept and minor changes were made to align to the [DSA style guide](https://design.dsausa.org/national-identity/color-palette/)

## Domain Name
TBD, needs to be agreed on but proposed to use chapter.dsausa.org as the backbone for these websites. Gitlab supports [custom domain names with https here](https://docs.gitlab.com/ee/user/project/pages/custom_domains_ssl_tls_certification/index.html)

## TODO
* Polish up instructions further, with screenshots
* Further details on how to make blog posts vs new pages in Jekyll
* Instructions on how to maintain and update pages with GitLab Editor vs Desktop
* Project website DNS name
