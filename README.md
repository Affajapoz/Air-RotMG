# Air-RotMG
Wrapped Realm of the Mad God in Air app

Use Air SDK.

adt -certificate -cn mycertificate 1024-RSA mycertificatefile.p12 password

adt -package -storetype pkcs12 -keystore mycertificatefile.p12 RotMG-Desktop.air application.xml redirect.html
