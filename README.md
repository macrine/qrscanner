# qrscan
cordova二维码扫描插件，基于phonegap-plugin-barcodescanner插件的界面修改，仿微信

--------------------------------

插件源代码：
https://github.com/phonegap/phonegap-plugin-barcodescanner  
安卓aar源代码：
https://github.com/EddyVerbruggen/barcodescanner-lib-aar  

插件安装：cordova plugin add phonegap-plugin-barcodescanner

## 安卓：
插件安装之后将项目中的barcodescanner.aar替换为本例中的[barcodescanner.aar](https://raw.githubusercontent.com/macrine/qrscanner/master/barcodescanner.aar)文件即可，也可自行修改代码再[生成aar文件](https://github.com/EddyVerbruggen/barcodescanner-lib-aar#steps-to-build-a-new-aar)。  
![android](https://raw.githubusercontent.com/macrine/qrscanner/master/screenshots/android.png) 

## ios：
插件安装之后将项目中的CDVBarcodeScanner.mm 替换为本例中的[CDVBarcodeScanner.mm](https://raw.githubusercontent.com/macrine/qrscanner/master/CDVBarcodeScanner.mm)文件。  
![ios](https://raw.githubusercontent.com/macrine/qrscanner/master/screenshots/ios.png)  
