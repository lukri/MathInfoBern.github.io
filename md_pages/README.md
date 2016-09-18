To create a new **page** with permalink from a markdown file, create here file `pagename.md` with the following form:

    ---
    layout: simple_article
    title: Some Title
    subtitle: Some subtitle
    permalink: /pagename/
    ---
    The page content styled with markdown.

    To add for example a link, use [Displayed Name](https://url.com)


Then add a **link** `{{base}}/pagename` to the `/_includes/header.html` file or another page.
The content could be styled with markdown, i just realised that lists are converted to html lists, but apparently aren't displayed as such by the template..
