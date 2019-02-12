# express-tool-cli
Tools to generate Express code
This tool expects your express project to follow this folder structure - 

```
- src
---- routes
---- controllers
---- helpers
---- models
- index.js (express is initialized here)
```

## Utility 1
- Generate code for an entity route
  express-tools-cli add entity
   -> name: 
   -> fields: -
       -> select datatype, other basic info for the type
       -> enter name
       -> continue till all fields added
   -> code is generated

