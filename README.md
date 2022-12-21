# jsbook
Notebook for javascript experimentation

1. Easy to use javascript experimentation tool.
2. Runs without backend (node.js/npm/pip install/ngnix etc etc)
3. Can be loaded from the web (i.e. behind a webserver) or from the file system   (certain features like WebRTC might require a server)
4. UI to be close to jupyter notebook (for familiarity)
5. Uses minimal external libararies and no frameworks (i.e. Vanilla JS). This is to increase the speed
6. Uses Codemirror for formatting the code area and pico Css for styling (https://picocss.com/)

## Use cases
1. Trying new libraries for testing and building
2. Building reproducable research and sharing the results with others

## Not to be used for:
1. Production applications
2. As an alternative to webapps

##How to use?
1. Clone this repository on any machine and double-click index.html. That's it. No Ngnix, no npm, no node, no pip install, no apt-get install.
2. If you want to host the the app online, you can put the folder in web directory of the server and use the link to index.html.
3. You can also try the git hosted version (wtihout downloading anything) here: https://gopi-suvanam.github.io/jsnb/index.html
4. For hello-world notebook check out: https://gopi-suvanam.github.io/jsnb/index.html#https://gopi-suvanam.github.io/jsnb/examples/Hello%20world.jsnb
5. You can download more examples from the folder examples/
