## Usage
1. run the workflow
2. use the resulting sources.txt file like this
```
ARGS=$(cat sources.txt); for a in $ARGS; do am -y -t https://github.com/"$a"; done
```
3. follow the on screen instructions
