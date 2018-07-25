# plantuml-contrib
Things to make PlantUML even better

# Installation/Use for JetBrains Projects on macOS

* Clone this repo somewhere you'd like, and make note of the location.  Assume the environment variable `REPO` contains the path to the cloned repo.
* Create a symlink in `~/Library/Preferences/$JETBRAINS_PRODUCT/templates` called `PlantUML.xml` and link it to `$REPO/ide/jetbrains/templates/PlantUML.xml`.  For example, for WebStorm 2018.1:
```
ln -s $REPO/ide/jetbrains/templates/PlantUML.xml ~/Library/Preferences/WebStorm2018.1/templates/PlantUML.xml
```
