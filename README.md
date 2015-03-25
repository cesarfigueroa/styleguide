# Style Guide

The following guide is an ongoing attempt to document the way I write code. It’s based on sensible practices shared by each respective community and personal opinion.

## General

Unless an interpreter or compiler dictates otherwise, these characteristics are consistent throughout all languages.

### File Naming

- Use the shortest extension possible (e.g. `.md` instead of `.mdown` or `.markdown`)
- Dasherize file names (e.g. `a-file-name.ext`)

### Whitespace

- Use soft-tabs, with a tab length of 2
- Keep lines below 80 characters in length (whenever possible)
- Omit trailing whitespace
- End each file with a blank line

## HTML

- End self-closing tags with a slash

  ```html
  <img src="photo.jpg" />
  ```

- Use bare attributes

  ```html
  <video src="trailer.mp4" loop controls></video>
  ```

## CSS

- Organize properties by alphabetical order

### Sass

- Place `@` directives above properties, and always place `@extend` before `@include`

  ```scss
  .module {
    @extend %clearfix;
    @include user-select(none);
  }
  ```

## Ruby

- Use curly braces for single line blocks and `do`/`end` for multiline.
- Long live the hashrocket!
