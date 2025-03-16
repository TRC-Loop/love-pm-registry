# Upload Packages

- Create a pull request
    - Briefly tell us what you package does.
    - Provide the valid .love_packagem file.
    - Check that the name is available.
    - Do not include malicious code.
    - Only include Lua and Asset files (png, jpg, gif, mp3, wav, json, yaml, txt, ...)
    - Test the package

> **Updating?**: Tell the version, and a brief changelog. 


# .love_packagem Spec

This is basically a .zip file, with another extension.

Structure:

```
.
├── prop.json
└── src/
    └── <code files>
```

`prop.json` example:

```
{
    "name": "love-pm-test",
    "version": 1.0
}
```

