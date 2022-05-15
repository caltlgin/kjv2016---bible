# kjv2016 [![AUR](https://img.shields.io/badge/AUR-kjv2016--git-blue.svg)](https://aur.archlinux.org/packages/kjv2016-git/)

Read the Word of God from your terminal

## Usage

    usage: ./kjv2016 [flags] [reference...]

      -l      list books
      -W      no line wrap
      -h      show help

      Reference types:
          <Book>
              Individual book
          <Book>:<Chapter>
              Individual chapter of a book
          <Book>:<Chapter>:<Verse>[,<Verse>]...
              Individual verse(s) of a specific chapter of a book
          <Book>:<Chapter>-<Chapter>
              Range of chapters in a book
          <Book>:<Chapter>:<Verse>-<Verse>
              Range of verses in a book chapter
          <Book>:<Chapter>:<Verse>-<Chapter>:<Verse>
              Range of chapters and verses in a book

          /<Search>
              All verses that match a pattern
          <Book>/<Search>
              All verses in a book that match a pattern
          <Book>:<Chapter>/<Search>
              All verses in a chapter of a book that match a pattern

## Build

kjv2016 can be built by cloning the repository and then running make:

    git clone https://github.com/bontibon/kjv2016.git
    cd kjv2016
    make

## License

Public domain
