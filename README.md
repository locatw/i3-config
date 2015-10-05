# i3-config
my i3 config

## i3 memo
Reference my Qiita article.

[タイル型ウィンドウマネージャのi3を試す + 備忘録 - Qiita](http://qiita.com/locatw/items/0a8a618b214a76d064a1)

## How To Set up
Make config directory if not exists.

    $ mkdir ~/config/
    
Clone this repository to config directory.

    $ cd ~/config/
    $ git clone https://github.com/locatw/i3-config

Create symblic link. (Make sure i3 is installed.)
    
    $ rm -rf ~/.i3/config
    $ ln -s ~/config/i3-config/config ~/.i3/config
