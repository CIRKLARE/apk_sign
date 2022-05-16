# apk_sign
sign apk files after compiling it

----------------------------------

this command to generate keystore

keytool -genkey -v -keystore key.jks -keyalg RSA -keysize 2048 -validity 10000 -alias my-alias

----------------------------------
this command to sign apk

apksigner sign --ks key.jks fin.apk

----------------------------------

and this to verify apk

apksigner verify fin.apk

----------------------------------
