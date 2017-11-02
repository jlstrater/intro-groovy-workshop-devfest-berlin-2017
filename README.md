# intro-groovy-gr8workshops
An Introduction to Groovy for the DevFest Berlin 2017

No longer a niche, scripting language, Groovy now exists in small and large organizations across the globe from Berlin startups like Zenjob to Netflix and Google. Whether part of a Jenkins script, Gradle config, Grails application, or Spock test, you may already be using or at least are aware of the Groovy programming language.

This introductory workshop aimed at experienced programmers new to groovy will highlight some basic syntax, explore basic scripting functionality, and finish with creating your first web application.

Slides are published at [https://jlstrater.github.io/intro-groovy-workshop-devfest-berlin-2017](https://jlstrater.github.io/intro-groovy-workshop-devfest-berlin-2017/)

# About the Slides

## Running Locally
This presentation is based on the [Object Partners Reveal Template](https://github.com/objectpartners/opi-reveal-template) which uses jade as a templating engine and grunt to run, reload, and publish the presentation to github pages.

* `npm install`
* `grunt assemble`
* `grunt run`

Source code is in the *src* folder.  The distrubution is in the *dist* folder. Be careful. Changes in *dist* will be overwritten by the next assemble or reload.

## Publishing to github
Github supports web hosting on the gh-pages branch of a repository(like this one!)

If you have forked this repository, the `grunt publish` task takes the dist folder and packages it on the gh-pages branch of your repository. Remember to run `grunt assemble` before publishing.
