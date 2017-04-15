## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/brain-flush/brain-flush.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

{% for post in site.posts %}
[{{post.title}}]({{post.url}})
{% endfor %}
