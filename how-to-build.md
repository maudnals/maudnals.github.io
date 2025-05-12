# How to build and deploy

- Package must be globally installed: `npm i markdown-to-html-cli -g`
- To build, run this: `markdown-to-html --source source.md --output index.html --style style.css --title "maudnals" --description "Maud Nalpas, Developer Relations Engineer, web developer, tech speaker" --favicon "data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🛰️</text></svg>"`
- Then push to GitHub. GitHub pages will automatically look for an index.html file (or for a README.md which is why I named mine source.md).
