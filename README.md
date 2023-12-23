<p align="center"><img src="https://portswigger.net/burp/communitydownload/images/burp-pro-logo.svg" alt="Burp Suite Professional logo" width="360" height="260"></p>

<h1 align="center">Welcome to Burp Suite loader👋</h1>

<div align="center">
 <a href="#"><img src="https://madewithlove.org.in/badge.svg"></a>
 <a href="https://buymeacoffee.com/cyb3rzest"><img src="https://img.shields.io/badge/buy%20me%20a%20Coffee%20-donate-red"></a>
 <a href="https://twitter.com/cyb3rzest/"><img src="https://img.shields.io/badge/twitter-%40CyberZeast-blue.svg"></a>
 <a href="https://github.com/cyb3rzest/Vasuki/issues"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat"></a>
 <a href="#"><img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg"></a>
 <a href="https://github.com/cyb3rzest?tab=followers"><img src="https://img.shields.io/badge/github-%40cyb3rzest-red"></a>
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
   <img src="https://img.shields.io/badge/green?color=gerrn&style=flat-square" alt="❤︎">
 </a>
</div>
<br>

<div align="center">

 ⚡️Burp Suite Professional 2023.*. * Loader Updated，Have Fun ⚡️<br><br>

For commercial use, please purchase genuine software - https://portswigger.net/buy/pro<br>

 ！ <a href="https://github.com/x-Ai/BurpSuiteLoader" >Old project</a> has been complained about by PortSwigger resulting in DMCA ! *Not obfuscated, please see the jar package for yourself*

</div>


#### **<p align="center" >✨If this project helps you, click Star (to Original Repository) 🥰✨</p>**



### BurpSuitePro Download


&ensp;&ensp;&ensp;&ensp;:https://portswigger.net/burp/releases/download?product=pro&version=2023.11.1.1&type=Jar

> wget -O burpsuite_pro.jar --quiet --show-progress https://portswigger.net/burp/releases/download?product=pro&version=2023.11.1.1&type=Jar

### Loader

Version I found only later that seemed to work better for me:

&ensp;&ensp;&ensp;&ensp;<a href="https://github.com/m41k1n4177/BurpSuite/blob/main/loader.jar">loader.jar</a>

> wget -O loader.jar --quiet --show-progress https://github.com/m41k1n4177/BurpSuite/blob/main/loader.jar

default loader provided by parent repo, also worked:

> wget -O BurpSuiteLoader.jar --quiet --show-progress https://github.com/m41k1n4177/BurpSuite/blob/main/BurpSuiteLoader.jar

&ensp;&ensp;&ensp;&ensp;<a href="https://raw.githubusercontent.com/x-Ai/BurpSuite/main/BurpSuiteLoader.jar">BurpSuiteLoader.jar</a>



#
## 🚀 Usage


<div align="center">

 <sub>！ We strongly recommend <b><u>AGAINST</u></b> downloading any all-in-one installer and using it ! </sub>
     <p>Try instead download Burp Pro from authentic source and based on steps provided in this repository, activate burp via launching burp with available loader</p>
</div>

# Burp Suite Professional Installation steps for ARCH LINUX (Untested/WIP)
   --> `paru -S burpsuite-pro \ `
       --> `zulu-19-bin \`
   --> `java-environment-common java-runtime-common jre-openjdk jre17-openjdk archlinux-java-run -y`
       --> `sudo archlinux-java set zulu-19`
   --> `echo "java --add-opens=java.desktop/javax.swing=ALL-UNNAMED--add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:$(pwd)/loader.jar -noverify -jar /usr/share/burpsuite-pro/burpsuite-pro.jar &" | sudo tee -a burpsuite`
       --> `chmod 777 burpsuite`
       --> `java -jar loader.jar ; & sleep 1s (./burpsuite)`


### Command line

Old

> java -noverify -Dsun.java2d.d3d=false -Dsun.java2d.noddraw=true --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED -javaagent:BurpSuiteLoader.jar -jar burpsuite_pro.jar

New

> java -noverify --add-opens=java.desktop/javax.swing=ALL-UNNAMED--add-opens=java.base/java.lang=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED --add-opens=java.base/jdk.internal.org.objectweb.asm.Opcodes=ALL-UNNAMED -javaagent:$(pwd)/loader.jar -jar burpsuite_pro.jar



## 📝 Discussion


If you have questions or better suggestions on how to use it, you can ask [issue](https://github.com/m41k1n4177/BurpSuite/issues).


## ❤️ Acknowledgements

shout out to the guy that got pwnd/ratted so hard he decided to go out and comment in every random burp loader GitHub repo that he was infected
```
