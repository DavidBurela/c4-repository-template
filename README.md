# Introduction
A template to help quickstart when modeling systems with https://c4model.com/ and https://structurizr.com/
- Script to easily start a local server
- Defaults in `structurizr.properties` to auto refresh the browser when `workspace.dsl` is updated
- `.gitignore` defaults for the structurizr generated files

Check the latest version at https://github.com/DavidBurela/c4-repository-template

## Suggested extensions
- VS Code: Syntax highlighting  
https://marketplace.visualstudio.com/items?itemName=ciarant.vscode-structurizr

## How to view a C4 model

### Online (for others wanting to quickly view)

1. Copy the contents of `workspace.dsl`
2. Go to <https://structurizr.com/dsl> 
3. Paste it into the window and click render.

### Local inner loop
This allows you to continuously edit, save the file, and see the rendered model auto refresh.

1. Run docker
2. From within the c4model folder, run `./start-structurizr.sh`
3. Browse to: <http://localhost:8080/>
