# TOC
1. [Quick Start](#quick-start)

# Quick Start

## Install Ruby Dev Environment
- https://jekyllrb.com/docs/installation/

## Fork Theme
- https://github.com/mmistakes/minimal-mistakes

## Remove Sample Code
- https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/#remove-the-unnecessary

## Add Github Pages Support
- https://github.com/benbalter/jekyll-remote-theme

## Install Bundler Package Manager
- ```gem install bundler```

## Install Dependancies
- https://mmistakes.github.io/minimal-mistakes/docs/installation/#install-dependencies

## Enable Live Local Updates
- replace the ```"jekyll"``` gem with
    + ```gem "github-pages", group: :jekyll_plugins```
- Run
    + ```bundle install```

## Start Jekyll
- Spin up local server
    + ```bundle exec jekyll serve```
    + browse ```localhost:4000```
- Build for remote
    + ```bundle exec jekyll build```

## Read Docs
Jekyll Docs
- https://jekyllrb.com/docs

MMistakes Docs
- https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/