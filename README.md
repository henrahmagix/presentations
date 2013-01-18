# Henry's Presentations

A collection of my talks. Each talk is a public gist, collated here via submodules.

+ [Nice Front End Things](https://gist.github.com/4557586) - Thursday 17th January, 2013 @ [JSOxford](http://twitter.com/jsoxford)
    + clone via ssh `git@gist.github.com:4557586.git`


## Cloning Gists

[gist.github.com](http://gist.github.com) now gives `git clone` urls as `https` rather than `ssh`. This will require entering your GitHub username and password _every time you push_.

Here is the __ssh__ url for a gist:

    git@gist.github.com:GIST_ID.git

For example, my [JSOxford](http://twitter.com/jsoxford) talk from 17th Jan 2013:

    git@gist.github.com:4557586.git



## Finding The Presented State

Most of my presentations are edited after they have been given. As such, every presentation will have a git tag of `presented` to which you can checkout:

    git checkout presented

Version tags keep track of edits after that. `v1.0` will always be the same as `presented`. I doubt the situation will _ever_ call for a `v2.0` tag, but you never know.
