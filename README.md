# rest-api-docs
Generate rest api documentation as a static web page with aglio and api blueprint. This is a simplified starting point example that includes file structuring required for complex api's. It requires node.js and npm.

## install aglio
```bash
npm install -g aglio
```

## build doc file using default theme 

```bash
aglio -i index.apib -o index.html
```


## build doc file using slate theme 

```bash
aglio  --theme-variables slate -i index.apib -o index.html
```

## references

[aglio](https://github.com/danielgtaylor/aglio)

[api blueprint](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md)
