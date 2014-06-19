# Certificate Plugin for Apache Cordova

## Introduction
Cordova Plugin to configure SSL Certificates, currently used to enable usage of untrusted  aka self-signed SSL certifcates


## install

```
cordova plugin add https://github.com/hypery2k/cordova-certificate-plugin.git
```

## Usage

Activate insecure certificates
```
cordova.plugins.certificates.trustUnsecureCerts(true)
```

Dectivate insecure certificates
```
cordova.plugins.certificates.trustUnsecureCerts(false)
```
