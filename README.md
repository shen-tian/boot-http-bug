# boot-http-bug
Reproducing a problem in [boot-http](https://github.com/pandeiro/boot-http) 0.7.3 (maybe)

Serving this folder with `python -m SimpleHTTPServer` works as intended.

Serving with `boot -d pandeiro/boot-http serve -d . wait` does not. Version 0.7.3.
