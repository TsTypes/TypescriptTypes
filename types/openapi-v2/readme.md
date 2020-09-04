# OpenApi version 2 types

These types are manually created from the specifications offered by the [OpenApi](https://github.com/OAI/OpenAPI-Specification/blob/master/versions/2.0.md) project.

# Geting started

In the tsconfig.json add:

-   `./node_modules/@tstypes` in the `typeroot` section
-   `openapi-v2` in the `types` section

# Example

```
"typeRoots": [
    "./node_modules/@tstypes"
],
"types": [
    "openapi-v2",
    "openapi-v3"
]
```
