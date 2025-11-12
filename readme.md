# 🗳️ CMSC 203 System Project

Introduction Statement for the Project

---

## 🛠️ Installation Steps
Follow these steps to install and configure the Program.

1. Before installing the program, make sure to download the following **extensions** on `VScode`;

    - Extention Pack for Java
    - Maven For Java

2. Install Maven using the Chocolatey installer in Powershell. Make sure that you've opened **Powershell** as **Administrator**.
    To download Chocolatey Input the following Code.<br>
    ```bash
        Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
    ```
        

    To install Maven using the Chocolatey's function, Input the following command on the same **Powershell Administartor Console**.   
    ```bash
        choco install maven -y
    ```

3. To Check **Maven's current version** input the following command on `bash`.

    ```bash
        mvn -v
    ```

    The following command must yeild the following text or atleast similar this.<br>
        `Apache Maven 3.9.11 (3e54c93a704957b63ee3494413a2b544fd3d825b)`<br>
        `Maven home: C:\ProgramData\chocolatey\lib\maven\apache-maven-3.9.11`<br>
        `Java version: 17.0.16, vendor: Eclipse Adoptium, runtime: C:\Program Files\Eclipse Adoptium\jdk-17.0.16.8-hotspot`<br>
        `Default locale: en_US, platform encoding: Cp1252`<br>
        `OS name: "windows 11", version: "10.0", arch: "amd64", family: "windows"`

4. If you've encountered an error check these following Sites or message me for help. : D
    - https://code.visualstudio.com/docs/java/java-gui
    - https://maven.apache.org/install.html


--- 

## 🚀 Options to Run The Program
- Run the Program on the Top Right
- On the Explorer Navigate to Maven > Plugins > javaFX > run
- Input the following code
    ```bash
        mvn javafx:run
    ```
---
## wait lang dito XD
https://gluonhq.com/products/scene-builder/