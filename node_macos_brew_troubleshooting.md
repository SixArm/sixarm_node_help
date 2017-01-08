# Node macOS brew troubleshooting

To fully reinstall Node, NPM, brunch, etc. do this:

    $ brew update
    $ brew uninstall node
    $ sudo rm -rf /usr/local/lib/node_modules
    $ brew install node --with-full-icu
    $ npm install -g npm
    $ npm install -g brunch

A full reinstall will solve this error:

    Error: Brunch 2+ requires node.js v4 or higher ...
    Upgrade node or use older brunch for old node.js: npm i -g brunch@1
