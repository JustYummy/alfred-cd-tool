# Alfred_cdTool_for_iTerm
This is based on [CDto](https://github.com/stidio/Alfred-Workflow)
### 1.How to use?
![pic](https://github.com/JustYummy/Alfred_cdTool_for_iTerm/blob/master/Pic/Pic1.png)
Type `cd ` + `folder name`
than select the folder you want
alfter that you will see
![pic](https://github.com/JustYummy/Alfred_cdTool_for_iTerm/blob/master/Pic/Pic2.png)
### 2.How to change the 'iTerm' to 'Terminal'
You can add a `#`before 
```osascript -e "tell application \"iTerm\" to open \"${DIR}\""```
and delete the `#` before
```#osascript -e "tell application \"Terminal\" to open \"${DIR}\""```
