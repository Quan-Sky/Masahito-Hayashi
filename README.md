Masahito Hayashi's Research Group
=================================

This is Masahito Hayashi's Research Group Website.

Features
--------

* Thanks to [Jekyll][jekyll], content is just text files. So even faculty should be able to figure it out.
* Publications list generated from Latex file using [Pandoc][pandoc].
* Personnel list. Organize your professors, students, staff, and alumni.
* Combined news stream and blog posts.
* Easily extensible navigation bar.
* Responsive (mobile-ready) design based on [Bootstrap][bootstrap].

Setup
-----

1. Install the dependencies. 
    1. [Python][python];
    2. [Jekyll][jekyll]:
        1. [Ruby][ruby] (check your Ruby version using `ruby -v`);
        2. [RubyGem][rubygem] (check your Gems version using `gem -v`);
        3. [GCC][gcc] and [Make][make] (check versions using `gcc -v`, `g++ -v`, and `make -v`);
        (Hint: for Wins, you can download MinGW for this dependency).
    3. [Pandoc][pandoc] (check versions using `pandoc -v`).
2. [Fork][fork] the **Research Group Website repository** on GitHub.
3. Clone the fork to your own machine: `git clone git@github.com:yourgroup/research-group-web.git`.
4. Add an "upstream" remote for the original repository so you can stay abreast of bugfixes: `git remote add upstream git://github.com/uwsampa/research-group-web.git`.
5. Customize. Start with the `_config.yml` file, where you enter the name of the site and its URL.
6. Use `make` command to build the site, and then run `make serve` to view your site. (If you find errors, please try `jekyll clean`.)
7. Keep adding content. See below for instructions for each of the various sections.
8. Periodically pull from the upstream repository: `git pull upstream master`.

Publication List
----------------

The list of publications is in `data/hayashi-publication.tex`. Typing `make` will generate `_includes/publication-list.html`, which contains a pretty, sorted HTML-formatted list of papers. This task is done by [Pandoc][pandoc].


News Items and Blog Posts
-------------------------

For both long-form blog posts and short news updates, we use Jekyll's blogging system. To post a new item of either type, you create a file in the `_posts` directory using the naming convention `YYYY-MM-DD-title-for-url.md`. The date part of the filename always matters; the title part is currently only used for full blog posts (but is still required for news updates).

The file must begin with [YAML front matter][yfm]. For news updates, use this:

    ---
    layout: post
    shortnews: true
    ---

For full blog posts, use this format:

    ---
    layout: post
    title:  "Some Great Title Here"
    ---

And concoct a page title for your post. The body of the post goes after the `---` in either case.

You can also customize the icon that is displayed on the news feed. By default it's `newspaper-o`. We use icons from the [FontAwesome][fa] icon set.

Projects
--------

To create a project, just create a markdown file in the `_projects` folder. Here are the things you can put in the YAML frontmatter:

- `title:` The project title.
- `notitle:` Set this to `true` if you don't want a title displayed on the project card. Optional.
- `description:` The text shown in the project card. It supports markdown.
- `people:` The people working on the project. This is a list of keys from the `_data/people.yml` file.
- `layout: project` This sets the layout of the actual project page. It should be set to `project`.
- `image:` The URL of an image for the project. This is shown on both the project page and the project card. Optional.
- `last-updated:` Date in the format of `YYYY-MM-DD`. The project cards are sorted by this, most recent first.
- `status: inactive` Set this to `inactive` if don't want the project to appear on the front page. Just ignore it otherwise.
- `link:` Set this to an external URL if this project has a page somewhere else on the web. If you don't have a `link:`, then the content of this markdown file (below the YAML frontmatter) will be this project's page.
- `no-link: true` Set this if you just don't want a project page for your project.

Personnel
---------

People are listed in a [YAML][YAML] file in `_data/people.yml`. You can list the name, link, bio, and role of each person. Roles (e.g., "Faculty", "Staff", and "Students") are defined in `_config.yml`.


Building
--------

The requirements for building the site are:

* [Jekyll][jekyll]: run `gem install jekyll`

`make` compiles the bibliography and the website content to the `_site` directory.
To preview the site, run `jekyll serve` and head to http://127.0.0.1:5000.

Remark
--------

This website a [Jekyll][jekyll]-based website updated from a templated for [research groups][sampa]. The Research Group project originated at the University of Washington.  You can see the machinery working live at [their site][sampa]. This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License][license].

<!--Compiler-->
[python]: https://www.python.org/
[ruby]: https://www.ruby-lang.org/en/downloads/
[rubygem]: https://rubygems.org/pages/download
[gcc]: https://gcc.gnu.org/install/
[make]: https://www.gnu.org/software/make/
<!--Dependencies-->
[jekyll]: https://jekyllrb.com/docs/installation/
[pandoc]: https://pandoc.org/
<!--Others-->
[YAML]: https://en.wikipedia.org/wiki/YAML
[yfm]: http://jekyllrb.com/docs/frontmatter/
[bootstrap]: http://getbootstrap.com/
[fa]: http://fontawesome.io/icons/
[fork]: https://github.com/uwsampa/research-group-web/fork
[sampa]: http://sampa.cs.washington.edu/
[license]: https://creativecommons.org/licenses/by-nc/4.0/
