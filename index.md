## Welcome to GitHub Pages

[Linkity link](https://google.com)

You can use the [editor on GitHub](https://github.com/matthewrecord/testblog/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Blog


{% for post in site.posts %}
### {{ post.title}}
{{ post.url}}

{{ post.content }}
{% endfor %}
