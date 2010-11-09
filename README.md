# Google Closure Bundle for TextMate

This is a TextMate bundle to help with Google Closure functions.

## Author

* Matt Bango (http://mattbango.com)

## Installation

### Install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/mattbango/google-closure-tmbundle.git "GoogleClosure.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

### Install without Git:
    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget http://github.com/mattbango/google-closure-tmbundle/tarball/master
    tar zxf mattbango-google-closure-tmbundle*.tar.gz
    rm mattbango-google-closure-tmbundle*.tar.gz
    mv mattbango-google-closure-tmbundle* "GoogleClosure.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'
