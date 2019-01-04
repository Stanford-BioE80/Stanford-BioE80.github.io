---
title: "Markdown and GitHub"
permalink: /docs/site_howto/
last_modified_at: 2018-11-25T22:21:33-05:00
toc: true
---

### Introduction to Markdown: How to edit files and add new materials

You can use the [editor on GitHub](https://github.com/Stanford-BioE80/Stanford-BioE80.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown - Basics

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

Here are some examples of what a post with images might look like. If you want to display two or three images next to each other responsively use `figure` with the appropriate `class`. Each instance of `figure` is auto-numbered and displayed in the caption.


### Markdown - Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Stanford-BioE80/Stanford-BioE80.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Markdown - Figures (for images or video)

#### One Up

<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg">
		<img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg">
	</a>
	<figcaption>
		<a href="http://www.flickr.com/photos/80901381@N04/7758832526/" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">
		Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.
	</figcaption>
</figure>

#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

```html
<figure class="half">
    <a href="/assets/images/image-filename-1-large.jpg"><img src="/assets/images/image-filename-1.jpg"></a>
    <a href="/assets/images/image-filename-2-large.jpg"><img src="/assets/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
```

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.JPG"><img src="http://placehold.it/600x300.jpg"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.