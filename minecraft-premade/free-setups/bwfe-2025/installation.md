---
description: Learn how to set up the cxSTUDIOS BWFE Server Setup with ease!
---

# Installation

## 1. Find your Download Source

All download links for this setup can be found in this [page](https://cxstudios.in/download/bwfe).

{% hint style="info" %}
Arena maps are seperate addon for this setup, and can be downloaded for free from [here](https://cxstudios.in/download/bwfe-arenas).
{% endhint %}

## 2. Unzip your Files

Find the zip file in your downloaded files from above link. You will need to unzip it to open the folder inside.

## 3. Upload to your Server

* Shut down your server and connect to it via FTP or SFTP (contact your server hosting provider if you don't know how to do this).
* You then need to delete/cut all the server files out of the main directory of your server. If you want to keep these files, you'll have to put them in another folder or download them somewhere else.
* Upload the `Server Files.zip` file to your server host. It should be the only file on there.
* Unzip the file; it should create many files in the main directory. Once the file has been unzipped, the `.zip` can be deleted.



## 3. \[ALT] Run Server on Windows

It's not recommended to run the server on Windows OS. You can run it only for testing purposes.

* Extract `Server Files.zip`  to a empty folder.
* Download Java 17 or 21 from official website. (Java 8 or 11 is not supported)
* Use `start server.bat` to start your server.

## 4. Choosing Right Java & Server Version

Newer Setups from cxSTUDIOS are based on newer java versions.

This setup supports Java version from 17 to 21.

But the server requires the PaperSpigot version 1.8.8 to run properly (PandaSpigot fork is recommended)

{% hint style="info" %}
**MINIMUM SERVER REQUIREMENT**

* Server Requires to be running on Java 17.
* Server Requires Paper 1.8.8 (Version can't be changed)
{% endhint %}

{% hint style="warning" %}
**IMPORTANT NOTICE**\
Server is required to be running on 1.8.8 version and Java 17. Players can join from newer MC Clients using ViaVersion Plugin.
{% endhint %}

## 5. Plugin Dependencies

You'll have to manually download these plugins:

1. BetterSocial ( [**FROM HERE**](https://www.spigotmc.org/resources/%E2%9C%85-bettersocial-1-8-%E2%80%A2-texture-database-regex-professional-look-hikaricp-support.83437/) **)**&#x20;
2. Citizens2 ( [**FROM HERE**](https://ci.citizensnpcs.co/job/citizens2/3478/) ) - Required
3. Parties ( [**FROM HERE**](https://www.spigotmc.org/resources/parties-an-advanced-parties-manager.3709/) )
4. LastLoginAPI ( [**FROM HERE**](https://www.spigotmc.org/resources/lastloginapi-api-to-handle-player-names-and-login-timestamps.66348/) )
