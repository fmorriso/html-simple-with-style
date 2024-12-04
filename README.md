# HTML Simple with CSS styling
A simple HTML project with CSS styling via SCSS.

## Important Notes

Since this project uses SASS for styling, you need to do one of two tings if you are going to 
want to change the styles used in this project:
1. Install the sass tool and have it watch for changes in `main.scss` so it can transpile it into `main.css`.
If you choose this option, you'll need to:
   1. Use `npm install -g sass`
   1. Open a command (or PowerShell) prompt.
   1. navigate to the `styles` subdirectory.
   1. issue `sass .:. --watch --source-map`
1. Use a smart IDE such as WebStorm together with a plug-in that watches for changes in `main.scss` and automatically 
updates `main.css`

## Tools Used

| Tool     |  Version |
|:---------|---------:|
| SASS     |    1.8.1 |
| WebStorm | 2024.3.0 |
| VSCode   |   1.95.3 |

## Change History

| Date       | Description                                   |
|:-----------|:----------------------------------------------|
| 2024-12-03 | Initial creation                              |
| 2024-12-04 | Add information on how to use sass |

## References
* [Sass Basics](https://sass-lang.com/guide/)
