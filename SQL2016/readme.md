# Build SQL 2016 database

## Download
### [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15#download-ssms)
### [SQL Server 2016](https://info.microsoft.com/ww-landing-sql-server-2016.html?culture=en-us&country=us)
### [JRE](https://www.oracle.com/java/technologies/downloads/#jre8-windows)
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/0d86177c-33fe-4c53-9fa3-612cc0db6e80) <br>
### [File 1 required during installation - download manually](https://go.microsoft.com/fwlink/?Linkld=836819&lcid=1033)
### [File 2 required during installation - download manually](https://go.microsoft.com/fwlink/?Linkld=850317&lcid=1033)

## Deployment
### Disable firewall on the server where you want to configure SQL DB
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/04c0cca1-2511-4926-bf53-98faff304160)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/7f16f01f-51cc-4d72-9474-ceae35a8f4df)

### Install [JRE](https://www.oracle.com/java/technologies/downloads/#jre8-windows) and reboot the server
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/0d86177c-33fe-4c53-9fa3-612cc0db6e80)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/fb597d65-ae2d-41e8-b1fa-e4341d14541c)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/a9ce7b59-04af-42d1-a39f-f8937610d4a4)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/b35474a9-ce7e-4434-9731-f420375dfab4)

### Download [SQL Server 2016](https://info.microsoft.com/ww-landing-sql-server-2016.html?culture=en-us&country=us) and launch it
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/f52dc269-94b1-4dc9-b173-da8b0cc07643)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/53f0073c-b3b6-4988-8e8b-2352193c77c7)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/df595c93-aecc-4f9a-8738-0cf1df3e87c5)

Download the media <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/5ba064a2-7e94-4b6d-8154-12e1be7fae07)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/d4849da1-8c58-44aa-80be-1e9dc80fb21c)

Wait until download is completed <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/5412da19-6999-477c-960a-690564cdd83c)

Enable fiie extension in the view <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/ad849932-6d85-4d51-a784-457613fc68c1)

Mount the ISO we downloaded <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/735ed58e-3b11-4298-8224-6fe120502974)

Run as admin <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/b665228c-37fe-4917-be90-a53dcbc34cd1)

Start `New SQL Server stand-alone installation or add features to an existing installation` <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/07d36227-2054-4179-a776-c06e5fef9de6)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/e3cafe49-8b94-42d8-a634-e17f42b25914)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/78d78996-5a77-4bdb-965e-710fb0d0ed67)

Enable option - "I accept the license terms" and Next <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/373149f4-fafd-4da4-80a7-7f3df717fbd0)

Wait for the installation requirements - Next <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/b497a20f-55cc-4323-b13d-65adddd2f77d)

You can choose to use the update to check security. Enable according to their way of working <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/9b8e7e88-4837-4b61-ac7b-ad19b3bfe9b0)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/8be743e5-68fb-4d9b-9726-a06c2fb3c20b)

Select all <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/d547ee1f-f27d-419c-98f6-a6982889e397)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/6e83d7f0-86a9-4357-b987-8ba13d5e12b2)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/a3aa5884-5abf-4053-afa9-6e826222ec18)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/4717d9a1-a381-4b91-9a8f-5d3c2edd81e2)

Set the type of instance to be used. You can use the default instance name or customed one <br>
Default one <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/19fffb07-c831-4a25-90a2-c9aaa090c7ac)

Customed one <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/58b01067-690d-45ff-a860-47d943483a9e)

Wait for the installation process <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/f206a95d-f298-4233-b267-fbae1fa24e76)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/5f0306a5-0bc8-4d53-ae2f-3d3d70253b84)

Click Next <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/918bfc93-8df0-4e91-b641-1950f096c707)

Add the Active Directory domain accounts to administrators Database <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/37bd60d7-b19b-48f0-9541-28fce7ebdc28)

If you use the Data Mining Analysis Services service account set and the tabular format <br>
If you are an experienced user mode the way that is necessary for carrying out their work <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/30627adb-6f8d-4c79-bd76-78016e2f2c80)

Reporting Service allows you to set up a dedicated server for your use or use it in an integrated format to SharePoint <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/281723b7-0829-4347-90dc-a9458ae18d4e)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/fc771cd2-df02-4e35-ade6-5258c79aecb5)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/c2c5c160-ef0b-4447-9db6-9105b5f72c76)

The Next button is disabled while the Accept button is not marked <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/7edd4de6-0dc7-45f3-a923-5ba28f2f38ff)

Manually select the path where you download [File 1](https://go.microsoft.com/fwlink/?Linkld=836819&lcid=1033) and [File 2](https://go.microsoft.com/fwlink/?Linkld=850317&lcid=1033) <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/a458f13a-8ffe-4a93-840c-8db328e04393)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/5011eb60-db84-4f90-9598-41d8dcccbdc6)

Click install <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/2a5da588-b2ee-4e80-a1f5-fe5fefd738d9)

![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/3017378d-8aea-4c38-ba50-9a0ac727414d)

Wait until installtion is completed <br>
![image](https://github.com/guguji666666/GJS-ADRMS/assets/96930989/74f3a5ca-01d4-430d-be7b-fda2122bd4b7)


