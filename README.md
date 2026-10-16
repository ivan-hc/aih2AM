## Usage
1. edit the aih2am file by changing the range in $ARG, this is the number of issues/pull requests in appimage.github.io
2. run the workflow https://github.com/ivan-hc/aih2AM/actions/workflows/lister.yml
3. use the resulting sources.txt file like this
```
ARGS=$(cat sources.txt); for a in $ARGS; do am -y -t https://github.com/"$a"; done
```
4. follow the on screen instructions
