# Introduction

This is a demonstration app based on Pocketsphinx on Android. In this demo, I write my own command text and
use [Sphinx Knowledge Base Tool](http://www.speech.cs.cmu.edu/tools/lmtool.html) to build language model files and
dictionary files.

## I change the demo as this:

### In module `app`

- modify source code of PocketSphinxActivity in package `edu.cmu.pocketsphinx.demo`
- add a new file named `icon_app.png` in `drawable-hdpi`
- write a new UI layout `main.xml` instead of original one
- change the content of strings.xml and AndroidManifest.xml

### In module `models`

- add file `test.dic` and `test.lm` into `src\main\assets\sync`

## Other Info

original demo address: https://github.com/cmusphinx/pocketsphinx-android-demo

See for [details](http://cmusphinx.sourceforge.net/wiki/tutorialandroid)