<p align="center"><img src="https://portswigger.net/burp/communitydownload/images/burp-pro-logo.svg" alt="Burp Suite Professional logo" width="360" height="260"></p>

<h1 align="center">Welcome to Burp Suite loader👋</h1>

<div align="center">
  <!-- Platform -->
  <a href="Platform">
    <img src="https://img.shields.io/badge/Platform-Windows%E3%80%81Linux%E3%80%81macOS-green?color=gerrn&style=flat-square" alt="Platform">
  </a>
  <!-- License -->
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/x-Ai/BurpSuite?color=gerrn&style=flat-square" alt="LICENSE">
  </a>
  <!-- ❤︎ -->
  <a href="❤︎">
    <img src="https://img.shields.io/badge/❤︎-致敬永远好奇的心-green?color=gerrn&style=flat-square" alt="❤︎">
  </a>
</div>
<br>

<div align="center">

  ⚡️Burp Suite Professional 2023.*. * Loader Updated，Have Fun ⚡️<br><br>

For commercial use, please purchase genuine software - https://portswigger.net/buy/pro<br>

  ！ <a href="https://github.com/x-Ai/BurpSuiteLoader" >Old project</a> has been complained about by PortSwigger resulting in DMCA ! *Not obfuscated, please see the jar package for yourself*

</div>


#### **<p align="center" >✨If this project helps you, click Star (to Original Repository) 🥰✨</p>**



<h1 align="center"></h1>

<br><p align="center" >The reason I built this project again after two years was because I saw Master SCZ's <a href="https://mp.weixin.qq.com/s/4KXxKdnPeWqsEsylObhg8w">public article</a> and thought I'd write a more detailed document to to help students who need it</p

<h1 align="center"></h1>



### BurpSuitePro Download


&ensp;&ensp;&ensp;&ensp;https://portswigger.net/burp/releases


### Loader


&ensp;&ensp;&ensp;&ensp;<a href="https://raw.githubusercontent.com/x-Ai/BurpSuite/main/BurpSuiteLoader.jar">BurpSuiteLoader.jar( 5.93KB)</a>

- SHA256: 23499F88ED11FA69E6A9BF5B17594B326EF71C631D28DA804F02C3EF08C68150

- MD5: 694738870DB8D69A6F1BEB6D05CD0999


### Windows 启动器源码

&ensp;&ensp;&ensp;&ensp;<a href="https://raw.githubusercontent.com/x-Ai/BurpSuite/main/BurpSuiteLoadSources.zip"> BurpSuiteLoadSources.zip(19.3KB)</a>

- SHA256: BDF5FAC98B8709532E721A75A6EFD491BFC54E09739436119BDBFCBCA12A82B5

- MD5: 91231D19E6EB35CCA959252EF01ECEA9


## 🚀 Usage


<div align="center">

  <sub>！ We strongly recommend downloading the installer to install it and use it ! </sub>

</div>


### Command line

> java -noverify -Dsun.java2d.d3d=false -Dsun.java2d.noddraw=true --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED -javaagent:BurpSuiteLoader.jar -jar burpsuite_pro.jar

### Windows

1. 下载：https://portswigger-cdn.net/burp/releases/download?product=pro&version=2022.3.1&type=WindowsX64

2. Place in the installation directory


<p align="center"><img src="/static/Launch.png" alt="Burp启动器"></p>

&ensp;&ensp;&ensp;&ensp;<a href="https://raw.githubusercontent.com/x-Ai/BurpSuite/main/BurpSuite.zip">BurpSuite.zip(9.15KB)</a>


- SHA256: 897AD7E16EC063EEAFAB9AEF4913851474B70594C0252354B2E69A09CA74C809

- MD5: 9C02C757FBE0163B54A7633D0BB91226


&ensp;&ensp;3. Using the compiled launcher


### macOS

1. Download macOS (Intel/M1)

2. Place the loader to the following path

> /Applications/Burp Suite Professional.app/Contents/java/app


<p align="center"><img src="/static/macOSLoader路径.png" alt=" macOSLoader path"></p>


&ensp;&ensp;3. Modify the contents of the following path file


> /Applications/Burp Suite Professional.app/Contents/Info.plist

<p align="center"><img src="/static/InfoPlistpath.png" alt="Info.plist path"></p>


&ensp;&ensp;4. Modify the Info.plist file by inserting the following statement after ``<string>-Dexe4j.moduleName=$APP_PACKAGE</string>`


```

......

<string>-Dexe4j.moduleName=$APP_PACKAGE</string>

<string>-noverify</string>

<string>-javaagent:$APP_PACKAGE/Contents/Resources/app/BurpSuiteLoader.jar</string>

```

&ensp;&ensp;5. Use the BurpSuite shortcut in the launchpad

## 💻展示


<p align="center"><img src="/static/Main.png" alt="BurpSuitePro"></p>



## 📝 Discussion


If you have questions or better suggestions on how to use it, you can ask [issue](https://github.com/x-Ai/BurpSuite/issues).


## ❤️ Acknowledgements 


- **surferxyz** && **scz** Both of you greats

- <a href="https://github.com/Hywell">Hywell</a> 


