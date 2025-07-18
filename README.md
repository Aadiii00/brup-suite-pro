# brup-suite-pro
Burp Suite Professional is a web application security testing tool that identifies vulnerabilities in web applications and web services.

install brup suite pro in kali linux latest version 2025

Steps to install Burp Suite Pro cracked on Kali Linux:

Note : We have used zshrc for setup, if you received any error related to zshrc then you can try using bashrc. For this you have to replace zshrc with bashrc

Download : https://drive.google.com/drive/folders/1HOQJTsjLL2hqGB-VMBxL5vvdInKesT8y
Download Java 8 : https://adoptopenjdk.net/releases.html?variant=openjdk8&jvmVariant=hotspot
If above link is not working properly please use below link to download java 8 : https://www.mediafire.com/file/c4bm2xybldz4p0w/OpenJDK8U-jdk_x64_linux_hotspot_8u292b10.tar.gz/file
Open Downloads folder
Open terminal in Downloads folder
Run : sudo su
Extract Java Archive file : tar -C /usr/lib/jvm -xzf OpenJDK8U-jdk_x64_linux_hotspot_8u292b10.tar.gz
Close Terminal
Extract Burp Archive file on Desktop
Open terminal in the same folder that is in Desktop
Run : sudo su
Run : java -jar burp-loader-keygen.jar
Open new terminal in the same folder that is in Desktop
Run : /usr/lib/jvm/jdk8u292-b10/bin/java -Xbootclasspath/p:burp-loader-keygen.jar -jar burpsuite_pro_v1.7.37.jar
Wait till burp loads and show the Enter License Key Screen
Now copy License from file burp-loader-keygen
Paste it in Burp Suite.
Click on Next
Click on Manual Activation
Copy : Activation Request from Burp Suite that is copy request
Past it into burp-loader-keygen file
You’ll receive Activation Response
Copy Activation Response from burp-loader-keygen file and paste it in Burp Suite.
Click on Next and then Finish.
Now go to terminal
Run : nano ~/.zshrc
Scroll to the bottom of the file
Add : alias burpro=”/usr/lib/jvm/jdk8u292-b10/bin/java -Xbootclasspath/p:/home/kali/Desktop/Burp\ Suite\ Pro/burp-loader-keygen.jar -jar /home/kali/Desktop/Burp\ Suite\ Pro/burpsuite_pro_v1.7.37.jar”
Note : Above path may be different for you. Please check and change it accordingly.
Save file : CTRL+O and Press Enter
Exit File : CTRL+X
Run : source ~/.zshrc
Close All terminals and Open new Terminal
Run : burpro
Thank You..!!!
