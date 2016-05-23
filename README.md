<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnormalian%2Feclipse-script-windows-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fnormalian%2Feclipse-script-windows-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

# Install JDK and Eclipse into Windows Server VM with ARM templates
This template deploys a Window Server including JDK and Eclipse like below.
- Eclipse: c:\opt\eclipse\ from http://mirrors.neusoft.edu.cn/eclipse/technology/epp/downloads/release/mars/2/eclipse-jee-mars-2-win32-x86_64.zip
- JDK: c:\zulu8.x.x-jdk8.xxxxxx\ from http://azure.azulsystems.com/zulu/zulu8.13.0.5-jdk8.0.72-win_x64.zip

And setup JAVA_HOME and PATH environment variables for launching Eclipse.


## Known Issues and Limitations
- none
