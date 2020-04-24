# Roses Revival App Jam website

This is the site for the Roses Revival app jam, hosted at jam.hacksoc.org.

## Building

The site is a single page, with a little bit of JavaScript for cookieless
Google Analytics.

The CSS is compiled from SCSS, so **do not edit style.css**. Instead, edit
style.scss and have this running while you make changes:

```
sass -w style.scss:style.css
```