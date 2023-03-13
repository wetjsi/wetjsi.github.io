# Welcome to Jekyll!
#
# This config file is meant for settings that affect your whole blog, values
# which you are expected to set up once and rarely edit after that. If you find
# yourself editing this file very often, consider using Jekyll's data files
# feature for the data you need to update frequently.
#
# For technical reasons, this file is *NOT* reloaded automatically when you use
# 'bundle exec jekyll serve'. If you change this file, please restart the server process.
#
# If you need help with YAML syntax, here are some quick references for you:
# https://learn-the-web.algonquindesign.ca/topics/markdown-yaml-cheat-sheet/#yaml
# https://learnxinyminutes.com/docs/yaml/
#
# Site settings
# These are used to personalize your new site. If you look in the HTML files,
# you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
# You can create any custom variable you would like, and they will be accessible
# in the templates via {{ site.myvariable }}.

title: Your awesome title
email: your-email@example.com
description: >- # this means to ignore newlines until "baseurl:"
  Write an awesome description for your new site here. You can edit this
  line in _config.yml. It will appear in your document head meta (for
  Google search results) and in your feed.xml site description.
baseurl: "" # the subpath of your site, e.g. /blog
url: "" # the base hostname & protocol for your site, e.g. http://example.com
twitter_username: jekyllrb
github_username:  jekyll

# Build settings
theme: minima
plugins:
  - jekyll-feed

# Exclude from processing.
# The following items will not be processed, by default.
# Any item listed under the `exclude:` key here will be automatically added to
# the internal "default list".
#
# Excluded items can be processed by explicitly listing the directories or
# their entries' file path in the `include:` list.
#
# exclude:
#   - .sass-cache/
#   - .jekyll-cache/
#   - gemfiles/
#   - Gemfile
#   - Gemfile.lock
#   - node_modules/
#   - vendor/bundle/
#   - vendor/cache/
#   - vendor/gems/
#   - vendor/ruby/

# The largest heading
## The second largest heading
###### The smallest heading

Style	Syntax	Tastenkombinationen	Beispiel	Output
Fett	** ** oder __ __	BEFEHL+B (Mac) oder STRG+B (Windows/Linux)	**This is bold text**	Dieser Text ist fett.

Kursiv	* * oder _ _     	BEFEHL+I (Mac) oder STRG+I (Windows/Linux)	*This text is italicized*	Dieser Text ist kursiv.

Durchgestrichen	~~ ~~		~~This was mistaken text~~	Dieser Text war falsch.

Fett und kursiv verschachtelt	** ** und _ _		**This text is _extremely_ important**	Dieser Text ist sehr wichtig.

Alles fett und kursiv	*** ***		***All this text is important***	Dieser gesamte Text ist wichtig.

Tiefgestellt	<sub> </sub>		<sub>This is a subscript text</sub>	Dies ist ein tiefgestellter Text.

Hochgestellt	<sup> </sup>		<sup>This is a superscript text</sup>	Dies ist ein h
