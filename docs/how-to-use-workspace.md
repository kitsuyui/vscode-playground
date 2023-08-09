# How to use Workspace

- [Multi-root Workspaces](https://code.visualstudio.com/docs/editor/multi-root-workspaces)

## On the application

### To create

- Select `File` > `Save Workspace As...` from the menu

### To open

- Select `File` > `Open Workspace...` from the menu

## On the command line

The file is actually written in JSON with comments in the file `{name}.code-workspace`.
On the command line, specify `code {name}.code-workspace` to open the workspace.
If you open it with `code .`, you will be assisted by a pop-up saying `This folder contains a workspace file 'example.code-workspace'. Do you want to open it? Learn more about workspace files.`, so select it.
