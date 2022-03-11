# VS Code config

```
    // Live Sass Compile
    "liveSassCompile.settings.formats": [
        // {
        //     "format": "expanded",
        //     "extensionName": ".css",
        //     "savePath": "./dist/"
        // },
        {
            "extensionName": ".min.css",
            "format": "compressed",
            "savePath": "./dist"
        }
    ],
    "liveSassCompile.settings.excludeList": [
        "**/node_modules/**",
        ".vscode/**"
    ],
    "liveSassCompile.settings.generateMap": false,
    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 2 versions"
    ]
```

