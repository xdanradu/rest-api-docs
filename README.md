# rest-api-docs
Generate rest api documentation asa static web page with aglio and api blueprint

## references

[aglio](https://github.com/danielgtaylor/aglio)

[api blueprint](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md)

## build doc using default theme 

```bash
aglio -i index.apib -o index.html
```


## build doc using slate theme 

```bash
aglio  --theme-variables slate -i index.apib -o index.html
```

