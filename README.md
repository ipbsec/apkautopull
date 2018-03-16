#apkautopull V2

apk auto pull is a script that wraps several adb calls to simplify the process of finding and pulling an apk from a connected Android device.

it takes an app name or partial name as a  parameter, finds the corresponding app and pulls the apk to the current directory.

There is a wiki page for this project - please see https://github.com/ipbsec/apkautopull/wiki

Usage

Single file
./apkautopull -s appname
eg: ./apkautopull -s chrome

Multiple files
./apkautopull -m bluetooth

Pull everything
./apkautopull -a

You are free to use for personal and commercial use. 
No warranty.
No support.
No Liability.

Apache 2
