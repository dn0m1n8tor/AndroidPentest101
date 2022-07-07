# Android Pentest 101 ![awesome](https://awesome.re/badge.svg)

<!-- Maintained by [@Anubhav Singh](https://twitter.com/AnubhavSingh_) with contributions from the security communities.
 -->
<!-- ## Introduction -->

<img src="/img/Android_Logo.jpeg" width="700" height="500">

### A curated list of Android Security materials and resources For Pentesters and Bug Hunters. This Repository will guide you on How to start with Android pentesting from scratch, enjoy it!!

---

<!-- ![Image](/img/Android_Logo.jpeg) -->

<!-- <img src="/img/Android_Logo.jpeg" width="700" height="500"> -->


## Basics 

1. Android Application Framework: Beginner’s Guide : <br> https://www.hackingarticles.in/android-application-framework-beginners-guide/

2. How Android OS Starts You Application : <br> https://proandroiddev.com/android-internals-101-how-android-os-starts-you-application-e1c98a014c05

3. The internals of Android APK build process : <br> https://medium.com/androiddevnotes/the-internals-of-android-apk-build-process-article-5b68c385fb20

4. Android Architecture : <br> https://payatu.com/blog/amit/Need-to-know-Android

5. Java for Android : <br> https://www.youtube.com/watch?v=fis26HvvDII

6. Environment setup for Android Pentesting: <br> 
	1. Use Mobexler for tools : <br> https://mobexler.com/setup.htm
	2. Emulator and Burpsuite Setup:
	    * Genymotion: <br> https://www.arridae.com/blogs/setting-up-an-android-pt-environment.php
	    * Nox Player: <br> https://medium.com/swlh/android-mobile-penetration-testing-lab-dfb8ceb4efbd
  
7. Understand Owasp Top 10:

	* Using DIVA

	  * Simple level : <br> https://danishzia.medium.com/diva-android-app-walkthrough-bce72b7f273a
	  * Code level : <br> https://reversingbinaries.in/diva-apk-analysis/

	* Aditya Agarwal Writeups (Go through all) <br> https://manifestsecurity.com/android-application-security/

8. Understand the working of tools:

	* apktool : <br> https://medium.com/@jasjot784/how-to-extract-source-code-of-an-apk-using-apktool-b5f601383ab
	
	* Dex2Jar : <br> https://github.com/pxb1988/dex2jar
	
	* JD-GUI : <br> https://nikhil-gandla777.medium.com/how-to-decompile-the-android-apk-file-to-a-jar-file-using-dex2jar-and-jd-gui-in-your-windows-47ea1ce3c410

	* MobSf : <br> https://www.hackingarticles.in/android-pentest-automated-analysis-using-mobsf/

9. APK Reversing

	* Apk Reverse Engineering : <br> https://www.hackingarticles.in/android-penetration-testing-apk-reverse-engineering/

	* APK Reversing (Part 2) : <br> https://www.hackingarticles.in/android-penetration-testing-apk-reversing-part-2/
 
	* Solve InjuredAndroid CTF : <br> https://github.com/B3nac/InjuredAndroid

10. Exploiting Insecure Firebase Database! : <br> https://blog.securitybreached.org/2020/02/04/exploiting-insecure-firebase-database-bugbounty/

11. Dumping Android application memory with fridump : <br> https://securitygrind.com/dumping-android-application-memory-with-fridump/

12. Android App Security & Testing : <br> https://infosecwriteups.com/android-app-security-testing-156a052ce7e8

## Intermediate 


1) Understand SSL Pinning Implementation and it's bypass : <br> https://redhuntlabs.com/ultimate-guide-to-android-ssl-pinning-bypass

2) Understand Root Detection Implementation and it's bypass : 
	
	* Using frida: <br> https://redfoxsec.com/blog/android-root-detection-bypass-using-frida/ 
	
	* Using Reverse engineering APK : <br> https://resources.infosecinstitute.com/topic/android-root-detection-bypass-reverse-engineering-apk/

	* Using Xposed : <br> https://medium.com/@cintainfinita/android-how-to-bypass-root-check-and-certificate-pinning-36f74842d3be

	* Using Magisk: <br> https://techviral.net/bypass-apps-root-detection-android/

	* Comparison of Different Android Root-Detection Bypass Tools: <br> https://medium.com/secarmalabs/comparison-of-different-android-root-detection-bypass-tools-8fd477251640

3) Intent Redirection, Intent spoofing and intent interception

	* Penetrate the Protected Component in Android Part -1 : <br> https://payatu.com/blog/amit/Penetrate_the_protected_component_in_android_Part-0

	* Penetrate the Protected Component in Android Part -2 : <br> https://payatu.com/blog/amit/Penetrate_the_protected_component_in_android_Part-2

4) WebView Attacks : <br>  https://www.hackingarticles.in/android-penetration-testing-webview-attacks/

5) Drozer : <br> https://www.hackingarticles.in/android-penetration-testing-drozer/

6) Android App Reverse Engineering 101 : <br> https://www.ragingrock.com/AndroidAppRE/

7) Frida : 
	
	* Workshop on Frida : <br> https://www.youtube.com/watch?v=Bwf3eyU-hi4 
	
	* Sharpening your FRIDA scripting skills with Frida Tool : <br> https://blog.securelayer7.net/sharpening-your-frida-scripting-skills-with-frida-tool/
	
	* Andromeda- GUI based Dynamic Instrumentation Toolkit powered by Frida : <br> https://www.youtube.com/watch?v=qOEaA2CNNmUhttps://blog.securelayer7.net/sharpening-your-frida-scripting-skills-with-frida-tool/
	
	* Configuring Frida with BurpSuite and Genymotion to bypass Android SSL Pinning : <br> https://arben.sh/bugbounty/Configuring-Frida-with-Burp-and-GenyMotion-to-bypass-SSL-Pinning/
	
	* Frida's Gadget Injection on Android: No Root, 2 Methods <br> https://fadeevab.com/frida-gadget-injection-on-android-no-root-2-methods/
	
	* Exploration of Native Modules on Android with Frida : <br> https://payatu.com/blog/amit/explore_android_native_modules_using_frida

7) Exploiting Android Fingerprint Authentication : <br> https://medium.com/@ashishf6/exploiting-android-fingerprint-authentication-25dd9263bd74

8) Bypass of Biometrics & Password Security Functionality For android : <br> https://infosecwriteups.com/bypass-of-biometrics-password-security-functionality-for-android-8e0174ac7cac

9) Android Hooking and SSLPinning using Objection Framework : <br> https://www.hackingarticles.in/android-hooking-and-sslpinning-using-objection-framework/

10) Android Security Tools : <br> https://reconshell.com/android-security-resources/

##  Mind Map

* https://www.xmind.net/m/GkgaYH/
* https://www.xmind.net/m/DVAq9V/
* https://www.mindmeister.com/1491593727?t=Sfx1JsQwYW

## Advance

Go deeper in what you have learned till now ... There are lot's of material avaialble on internet to learn from. I will mention some of them which will help you to move further.

* Mobile Application Penetration Testing Cheat Sheet : <br> https://github.com/tanprathan/MobileApp-Pentest-Cheatsheet
* Awesome-Android-Security : <br> https://github.com/saeidshirazi/awesome-android-security
* AllThingsAndroid : <br> https://github.com/jdonsec/AllThingsAndroid
* awesome-mobile-security : <br> https://github.com/vaib25vicky/awesome-mobile-security
* Android-Pentesting : <br> https://github.com/pollonegro/Android-Pentesting


## Contributions
Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@AnubhavSingh_](https://twitter.com/AnubhavSingh_)

## Support

* Love it? Buy me a Tea when you meet me outside (preferred) 🥤 or via <br> <a href="https://www.buymeacoffee.com/anubhavsingh" target="_blank"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20Chai&emoji=%E2%98%95&slug=anubhavsingh&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" alt="Buy Me A Chai"></a>





