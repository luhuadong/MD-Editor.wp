# MD-Editor.wp

Markdown editor for WordPress

创建该项目的想法是 WordPress 市场中提供的 Markdown editor 插件都无法满足我们的需求，同时有一些能用的插件缺乏维护，所以索性自己创建一个项目进行修改维护。该项目在创建之初主要参考以下两个项目：

- [wp-editormd](https://github.com/LuRenJiasWorld/WP-Editor.md)
- [wp-githuber-md](https://github.com/terrylinooo/githuber-md)

## Requirement

* PHP version > 5.3.0
* WordPress version > 4.0
* Tested up to 5.5.1

## Download

| source | download | 
| --- | --- | 
| WordPress | https://wordpress.org/plugins/MD-Editor.wp |
| GitHub repository | https://github.com/luhuadong/MD-Editor.wp/releases | 
| PHP Composer | `composer create-project luhuadong/MD-Editor.wp MD-Editor.wp` |

## Installation

1. Upload the plugin files to the `/wp-content/plugins/MD-Editor.wp` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the `Plugins` screen in WordPress.
3. Go to the `MD-Editor.wp` menu in Plugins and set your Markdown options.

## Suggestions

The better situation to use this plugin is you just started a new blog.

If you're planning to use this plugin in an existing blog, be sure to:

- Turn off other Markdown plugins, because the similar plugins might do the same things when submitting your posts, may have some syntax conversion issues between Markdown and HTML.
- My personal suggestion is to turn off `revision` and `auto-save`, there are options in setting page.

## Features

* All-in-one [Markdown editor](https://markdown-editor.github.io/).
* Live preview.
* Spell check.
* Enable / disable Markdown for single post.
* Support Gutenberg editor.
* Support custom post types.
* HTML-to-Markdown helper
* Image copy & paste (support uploading to Imgur.com and sm.ms)
* Syntax highlight.
* Flow chart.
* KaTex.
* Sequence diagram.
* Mermaid.
* MathJax.
* Emoji.
* Github flavored Markdown task list.
* Markdown extra...
* Keyword suggestion tool.

