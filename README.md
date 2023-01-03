# Microbit Makecode Development Environment
A simple development environment for working on microbit makecode extensions. To use it:

```bash
# set up the development environment
git clone https://github.com/aogriffiths/microbit-makecode-dev-environment
cd microbit-makecode-dev-environment
npm install

# get a project for developing
mkdir projects
git clone <your project>

# run the makecode editor
cd ..
npm run serve &
```

This will open the makecode editor in your browser, but by default it will start serving projects fro your local storage. To access projects in the project folder created above add `?ws=fs` too the URL as follows [http:\\localhost:3232/index.html?ws=fs]().

You should now see the project you cloned above. You can edit and test it in the makecode editor and when you're ready commit you changes using git. You'll may need two shells, one for serving the makecode editor, and another for working on your project.
