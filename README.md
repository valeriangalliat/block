Block
=====

Blur lock.

Description
-----------

Locks the screen using `i3lock` with a blurred screenshot as background.

Idea taken from [here](http://plankenau.com/blog/post-10/gaussianlock).

Dependencies
------------

- `import` and `mogrify` (from `imagemagick`)
- `i3lock`

Options
-------

- `-d`: Print all dependencies (convenient to test if all dependencies are
  met with  `command -v $(block -d)`).
