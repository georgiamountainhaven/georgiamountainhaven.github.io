## references

* https://gohugo.io/getting-started/quick-start/
* https://bwaycer.github.io/hugo_tutorial.hugo/tutorials/creating-a-new-theme/
* https://toml.io/en/
* https://spec.commonmark.org/current/

## Deployment

1. commit changes
1. build the content, `hugo`
1. checkout the gh-pages branch
1. copy static content to docs/
1. add the updated docs/
1. commit
1. push
1. checkout the main branch

## Adding news

1. Create new news page, with today's date: `huge new page news\``date +%Y-%m-%d``.md`
1. Edit page for news content
1. Check sample, visible from `hugo -D serve`
1. Commit change
1. Deploy, see above instructions

