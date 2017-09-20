# BaiduPush
This repository contains Baidu's "Cloud Push" library for sending Push Notifications to mobile devices in China

We were not able to find any official license for the Baidu Cloud Push library. (This seems to be common in China for public domain code.) The best we could find was here:

http://push.baidu.com/doc/guide/licence

This is really more of a "Terms of Use" agreement that doesn't actually spell out our rights.

Tatia Chao of our partner IoT ONE (tatia.chao@iotone.com) said this in an email on 9/20/17:

> I've talked with several local developers regarding this. 
>
> It seems that in China we don't have the same license for push services as you mentioned. But as a common platform with a quite large user base, they don't think there are any risk issues as far as the licensing goes. 


We had to resort to this library because Android mobile devices in China behind the Great Firewall do not have access to most Google APIs, including Firebase. This provides an alternative way to send push notifications to mobile devices. The only place we use this code is in PushManager.groovy.

The documentation for this library is found here: 

http://push.baidu.com/doc/java/api

The download page is here: 

http://push.baidu.com/sdk/push_server_sdk_for_java

Which points to the actual download zip file: 

http://boscdn.bpc.baidu.com/channelpush/Baidu-Push-Server-SDK-Java-3.0.1.zip

Version 3.0.1 is dated 2015-06-15

