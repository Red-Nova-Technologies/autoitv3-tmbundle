# AutoIt3 Bundle for TextMate

This is a TextMate bundle to help with editing AutoItv3 scripts in either Textmate or e-TextEditor.

## License

The MIT License (MIT)
Copyright (c) 2011 Red Nova Technologies

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Install

The quickest way to install the bundle is via the command line. If you have Git installed, you'll probably want to install with Git. With or without, you can simply copy and paste each line one by one into the Terminal instructions ( lifted from [kswedberg](https://github.com/kswedberg/jquery-tmbundle) which was in turn lifted from [drnic](http://github.com/drnic/ruby-on-rails-tmbundle) ):

### Install with Git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/rhyddereh/autoitv3-tmbundle.git "AutoItv3.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

### Install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget https://github.com/rhyddereh/autoitv3-tmbundle/tarball/master
    tar zxf rhyddereh-autoitv3-tmbundle*.tar.gz
    rm rhyddereh-autoitv3-tmbundle*.tar.gz
    mv rhyddereh-autoitv3-tmbundle* "AutoItv3.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

## Download

If you'd like to avoid the command line altogether, you can download the bundle and install it:

1. download the zip from [https://github.com/rhyddereh/autoitv3-tmbundle/tarball/master](https://github.com/rhyddereh/autoitv3-tmbundle/tarball/master)
2. find the zip file on your local machine and double-click to unzip it
3. change the file name from *rhyddereh-autoitv3-tmbundle-really_long_alpha_numeric_sequence* to *AutoItv3.tmbundle* (with a dot rather than a hyphen).
4. double-click the *AutoItv3.tmbundle* file
5. open TextMate and select the following menu item: *Bundles > Bundle Editor > Reload Bundles*
6. show the Bundle Editor (*Bundles > Bundle Editor > Show Bundle Editor*)
7. scroll through the list of bundles to confirm that the bundle has been properly installed
