# rest-api-docs
Generate rest api documentation asa static web page with aglio and api blueprint

##References

[aglio](https://github.com/danielgtaylor/aglio)

[api blueprint](https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md)

## build doc using default theme 
aglio -i index.apib -o index.html

## build doc using slate theme 
aglio  --theme-variables slate -i index.apib -o index.html

## you can use the build.bat file to build the doc file
