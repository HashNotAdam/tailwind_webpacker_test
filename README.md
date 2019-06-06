# Tailwind/Webpacker proof of issue

There appears to be an issue when using Tailwind 1.0.1 in Rails 5.2.x with Webpacker whereby all media queries are now added to the stylesheet after custom styles regardless of where their import statement is in an SCSS file.

This repo is the simpliest reproduction of the issue for the sake of debugging