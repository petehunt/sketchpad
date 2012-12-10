sketchpad
=========

So you're a designer and you're building a mock or prototype in HTML/CSS. You quickly
get to the point where you want to reuse code (i.e. the chrome between multiple pages).
Sketchpad is a server that serves up the current directory and runs Jinja (Django
templates) on all html files in there. Pretty simple, but pretty useful too.

How to use
==========

Create a static site. Put Jinja markup in your html files. Run python -m sketchpad in the
root directory. Visit http://localhost:8080/. You can optionally provide which port you
want to run on as a command-line argument.