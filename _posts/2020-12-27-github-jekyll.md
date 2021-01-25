---
title: Github Blogging with Jekyll
tags:
  - github
  - jekyll
---

Websites for you and your projects.

# Create Github Repository
[GitHub Pages](https://pages.github.com/)

# Select Jekyll Theme
[GitHub Jekyll Themes](https://github.com/topics/jekyll-theme)

# Create Gemfile
```bash
source "https://rubygems.org"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
```

# Copy and edit _config.yml
```yml
remote_theme: daattali/beautiful-jekyll@5.0.0
language: en
...
```

# Create index.html
```markdown
---
layout: home
---
```

# Create _posts/YYYY-MM-DD-name.md
```markdown
---
title: Github Blogging with Jekyll
tags:
  - github
  - jekyll
---

Websites for you and your projects.

# Create Github Repository
[GitHub Pages](https://pages.github.com/)

# Select Jekyll Theme
[GitHub Jekyll Themes](https://github.com/topics/jekyll-theme)
...
```

# References
- [Jekyll](https://jekyllrb.com/)
- [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll)
