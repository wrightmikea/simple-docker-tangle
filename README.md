simple-docker-tangle
===

* An example of using Org mode, babel, and tangle to set up a shell session with a docker environment, generate a Dockerfile, build a named docker image, and run it with a shared directory.

Usage
===

* Edit the sdt.org file (in an emacs that supports orgmode, e.g, 24)
* Run the setup shell source blocks (using C-c C-c and respond yes to prompts))
* Generate the build/Dockerfile (using C-c C-v t in the dockerfile source block)
* Run the remaning shell source blocks

To regenerate the .html file
===

* Edit the sdt.org file
* Export to html (C-c C-e h o and then respond yes to prompts)

Sample exported .html
===
Browse [sample output](http://wrightmikea.github.io/simple-docker-tangle.html "exported html")
