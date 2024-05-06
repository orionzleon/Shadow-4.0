# Shadow Client 4.0

**Click [here](https://github.com/PeytonPlayz595/Shadow-4.0/actions?query=branch%3Amain+event%3Apush) for the latest downloads**

## Building the web/offline version

1. Clone this github repo
2. cd into the directory of this repo
3. Run `./gradlew generateJavaScript`
4. If you want the offline download, run `bash ./MakeOfflineDownload.sh`

## Running the Desktop Runtime

**Note: Requires a physical display to run, will NOT run on codespaces, ANY online terminal without a graphical display, or ANY ssh without X11 forwarding (Pretty much self explanitory but for the people who didn't know)**

**If you STILL don't understand, it basically means you have to run it on YOUR personal computer. You most likely will not be able to use it in a browser VM without a graphical interface or over SSH**

1. Clone this Github repo
2. cd into the directory of this repo
3. Run `./gradlew runClient` and wait for it to finish compiling
