# Task Automation

Task automation involves utilizing tools that are designed to automate
repetive day to day actions in order to streamline or augment a workflow.
Manually performing meticulous actions is generally not the most productive way
to approach a situation. If there are tools available that can make your life
easier why not use them?

We use a lot of task automating and task running tools while developing. I was
curious as to what some of these tools were and decided to research a bit about
them.

## Prerequisites

-   An open mind

## Objectives

By the end of this, developers should be able to:

-   Recieve an overview of task automation & task running.
-   Overview examples of task automation & task running tools that we use daily.
-   View the implementation of a task automation tool.


## Preparation

1.  Fork and clone this repository if you would like a copy of these notes.
 [FAQ](https://github.com/ga-wdi-boston/meta/wiki/ForkAndClone)

## Automation

Broad examples of automation in day to day life.
 - Using hotkeys.
 - Macros (logs your keystrokes, mouse movements, clicks, saves them to a file
 for later use)
 - Send timed e-mails to subscribers of a businesses email list
 (ActiveCampaign, Salesforce)
 - Amazon warehouse robots: https://www.youtube.com/watch?v=cLVCGEmkJs0

## Task automation and Development

We often use linters and other beautifing tools while coding, these are designed
to help us focus on writing nice and readable code. This is important when
writing code that other developers will use.

Automating development:
- Atom (packages, linter-csslint, linter-eslint, linter-rubocop)
- Visual Studio (places the terminal in your IDE)
- Task runners (rake, grunt, gulp)
- Bundler (webpack - bundles our modules for use in a browser environment)


## A Note on Task Runners

Some tools help us write beautiful code, while others help implement the
programs we write in a more functional perspective. Task runners help developers
perform a variety of actions such as concatenating/minifying files, and prefixing
files for different browsers. These tasks are possible to perform by writing
bash bash/shell scripts or npm package/commands. However, this could be quite time
consuming.

Let's take a look at grunt.

What does grunt do?
  - automates tasks such as minification (uglify), compilation, unit testing
  - allows us to use plugins such as handlebars, SASS, etc.

How does grunt work?
  - installed and managed via npm
  - configured with Gruntfile (configure & create custom tasks, load plugins)

Grunt commands:
- grunt lint: checks your JavaScript against JSHint
- grunt qunit: runs your Qunit tests
- grunt concat: concatenates your project files together and puts the new file
- grunt min: minifies the file concat put out.


## Work Smarter Not Harder

Demo task automation with Ruby. 
Disclaimer: I did this for science.

https://github.com/tarraschk/TinderAutoLike/blob/master/TinderAutoLike.rb

Failed trials: 
  - virtual box, android running as virtual machine, auto clicker
  - python script, charles proxy, fb auth token and id.


## Additional Resources

-   https://www.charlesproxy.com/documentation/getting-started/
-   https://github.com/jaungiers/Tinder-py_auto_liker/blob/master/tinder-py_auto_liker.py
-   https://medium.com/@malimirkeccita/how-to-automate-development-with-atom-4b27b1391e3f
-   https://www.visualstudio.com


## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
