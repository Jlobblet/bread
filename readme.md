Bread.

![](./static/bread.gif)

----

Would you like to contribute?

Open this up in VS Code, use the remote containers extension with docker and you should be set up to run!

In a container terminal (within the container), run `janet src/main.janet` and you should be able to reach the application at http://localhost:8000
**This process does not auto-reload, so `ctrl+C` and re-run to take on any changes.**

_Should you wish to change the port, set the `PORT` environment variable like so: `PORT=9999 janet src/main.janet`._

You'll know if you're in the container if it says `vscode -> /workspaces/bread` in the console.
