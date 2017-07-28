# Purpose

This example app opens up a new tab and demonstrates cross window communication.
It can be combined with an oauth setup to enable authentication in a new window
rather than the typical redirect based approach.

# Usage

1. `npm build`
1. `npm install -g serve`
1. `serve -s build`
1. `open http://localhost:5000/`
1. Click the button to open a new tab

The tab will send a message back to the origin window and immediately close.

# Credit

* create-react-app
* https://gist.github.com/gauravtiwari for the (slightly modified) postMessage logic

