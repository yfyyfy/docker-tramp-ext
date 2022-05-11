# docker-tramp-ext - Extensions for docker-tramp

`docker-tramp-ext.el` offers utility functions for [docker-tramp](https://github.com/emacs-pe/docker-tramp.el).

## Configuration

``` elisp
(require 'docker-tramp-ext)
```

## Usage

Use <kbd>M-x docker-tramp-ext-find-corresponding-file</kbd> to open the corresponding local/remote file of the current buffer.  
To keep the original buffer, use <kbd>C-u M-x docker-tramp-ext-find-corresponding-file</kbd>.  
To keep the original buffer and leave the point on the new buffer unchanged, use <kbd>C-u C-u M-x docker-tramp-ext-find-corresponding-file</kbd>.
