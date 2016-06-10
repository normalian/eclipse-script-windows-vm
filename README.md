<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fnormalian%2Feclipse-script-windows-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fnormalian%2Feclipse-script-windows-vm%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

# Install JDK and Eclipse into Windows Server VM with ARM templates
This template deploys a Window Server including JDK and Eclipse from below links.
- Eclipse: c:\opt\eclipse\ from http://mirrors.neusoft.edu.cn/eclipse/technology/epp/downloads/release/mars/2/eclipse-jee-mars-2-win32-x86_64.zip
- JDK: c:\zulu8.x.x-jdk8.xxxxxx\ from http://azure.azulsystems.com/zulu/zulu8.13.0.5-jdk8.0.72-win_x64.zip

And setup environment variables JAVA_HOME and PATH for launching Eclipse.

You can get a Zulu JDK links from <a href="https://azure.microsoft.com/documentation/articles/azure-toolkit-for-eclipse/">Azure Toolkit for Eclipse</a>.
You can get a Eclipse download link from https://eclipse.org/downloads/. You should take care to pick up Eclipse link for this template parameter, because "http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/mars/R/eclipse-jee-mars-R-win32-x86_64.zip&mirror_id=1109" uri is a just web page and browser redirect to actual link.

## Known Issues and Limitations
- none
