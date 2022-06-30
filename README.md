Thanks to:

## Collaborators

<!-- readme: collaborators -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/MichaelHilton">
            <img src="https://avatars.githubusercontent.com/u/1170420?v=4" width="100;" alt="MichaelHilton"/>
            <br />
            <sub><b>Michael Hilton</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: collaborators -end -->

## Contributors

<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/clegoues">
            <img src="https://avatars.githubusercontent.com/u/2806090?v=4" width="100;" alt="clegoues"/>
            <br />
            <sub><b>Claire Le Goues</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/MichaelHilton">
            <img src="https://avatars.githubusercontent.com/u/1170420?v=4" width="100;" alt="MichaelHilton"/>
            <br />
            <sub><b>Michael Hilton</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/rohanpadhye">
            <img src="https://avatars.githubusercontent.com/u/4233266?v=4" width="100;" alt="rohanpadhye"/>
            <br />
            <sub><b>Rohan Padhye</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/cmeiklejohn">
            <img src="https://avatars.githubusercontent.com/u/44939?v=4" width="100;" alt="cmeiklejohn"/>
            <br />
            <sub><b>Christopher S. Meiklejohn</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/namdy0429">
            <img src="https://avatars.githubusercontent.com/u/6078004?v=4" width="100;" alt="namdy0429"/>
            <br />
            <sub><b>namdy0429</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/victorhuangwq">
            <img src="https://avatars.githubusercontent.com/u/5773562?v=4" width="100;" alt="victorhuangwq"/>
            <br />
            <sub><b>Victor Huang</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/MilaHika">
            <img src="https://avatars.githubusercontent.com/u/43727139?v=4" width="100;" alt="MilaHika"/>
            <br />
            <sub><b>MilaHika</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Hita-K">
            <img src="https://avatars.githubusercontent.com/u/68398983?v=4" width="100;" alt="Hita-K"/>
            <br />
            <sub><b>Hita-K</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->




# Just the Class

Just the Class is a GitHub Pages template developed for the purpose of quickly deploying course websites. In addition to serving plain web pages and files, it provides a boilerplate for:

- a [course calendar](calendar.md),
- a [staff](staff.md) page,
- and a weekly [schedule](schedule.md).

Just the Class is built on top of [Just the Docs](https://github.com/pmarsceill/just-the-docs), making it easy to extend for your own special use cases while providing sane defaults for most everything else. This means that you also get:

- automatic [navigation structure](https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/),
- instant, full-text [search](https://pmarsceill.github.io/just-the-docs/docs/search/) and page indexing,
- and a small but powerful set of [UI components](https://pmarsceill.github.io/just-the-docs/docs/ui-components) and authoring [utilities](https://pmarsceill.github.io/just-the-docs/docs/utilities).

## Getting Started

Getting started with Just the Class is simple.

1. Create a [new repository based on Just the Class](https://github.com/kevinlin1/just-the-class/generate).
1. Update `_config.yml` and `index.md` with your course information.
1. Configure a [publishing source for GitHub Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages). Your course website is now live!
1. Edit and create `.md` [Markdown files](https://guides.github.com/features/mastering-markdown/) to add your content.

For a few open-source examples, see the following course websites and their source code.

- [CSE 390HA](https://courses.cs.washington.edu/courses/cse390ha/20au/) ([source code](https://gitlab.cs.washington.edu/cse390ha/20au/website)) is an example of a single-page website that centers modules.
- [CSE 143](https://courses.cs.washington.edu/courses/cse143/20au/) ([source code](https://gitlab.cs.washington.edu/cse143/20au/website)) hosts an entire online textbook with full-text search.
- [CSE 373](https://courses.cs.washington.edu/courses/cse373/21su/) ([source code](https://gitlab.cs.washington.edu/cse373-root/21su/website) is an example of a simple website combining Markdown pages with generated HTML files.

Share your website with us in the [show and tell discussion](https://github.com/kevinlin1/just-the-class/discussions/categories/show-and-tell)!

Continue reading to learn how to setup a development environment on your local computer. This allows you to make incremental changes without directly modifying the live website.

### Local development environment

Just the Class is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special Jekyll plugins and can run on GitHub Pages' standard Jekyll compiler.

1. Follow the GitHub documentation for [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll).
1. Start your local Jekyll server.
```bash
$ bundle exec jekyll serve
```
1. Point your web browser to [http://localhost:4000](http://localhost:4000)
1. Reload your web browser after making a change to preview its effect.

For more information, refer to [Just the Docs](https://pmarsceill.github.io/just-the-docs/).
