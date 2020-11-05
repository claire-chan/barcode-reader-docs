---
layout: default-layout
title: Dynamsoft Barcode Reader Java API Reference - DMLTSConnectionParameters Class
description: This page shows the DMLTSConnectionParameters Class of Dynamsoft Barcode Reader for Java SDK API Reference.
keywords: DMLTSConnectionParameters, class, api reference, java
needAutoGenerateSidebar: false
---


# DMLTSConnectionParameters

Defines a struct to configure the parameters to connect to license tracking server.  



## Attributes
    
| Attribute | Type |
|---------- | ---- |
| [`mainServerURL`](#mainserverurl) | *String* |
| [`standbyServerURL`](#standbyserverurl) | *String* |
| [`handshakeCode`](#handshakecode) | *String* |
| [`sessionPassword`](#sessionpassword) | *String* |
| [`deploymentType`](#deploymenttype) | *int* |
| [`chargeWay`](#chargeway) | *int* |
| [`uuidGenerationMethod`](#uuidgenerationmethod) | *int* |
| [`maxBufferDays`](#maxbufferdays) | *int* |
| [`limitedLicenseModules`](#limitedlicensemodules) | *int[]* |


### mainServerURL

The URL of the license tracking server.

```java
String com.dynamsoft.barcode.DMLTSConnectionParameters.mainServerURL
```

- **Value range**   
    Any string value   
      
- **Default value**   
    null

### standbyServerURL

The URL of the standby license tracking server.

```java
String com.dynamsoft.barcode.DMLTSConnectionParameters.standbyServerURL
```

- **Value range**   
    Any string value   
      
- **Default value**   
    null

### handshakeCode

The handshake code.

```java
String com.dynamsoft.barcode.DMLTSConnectionParameters.handshakeCode
```

- **Value range**   
    Any string value   
      
- **Default value**   
    null

### sessionPassword

The session password of the handshake code set in license tracking server.

```java
String com.dynamsoft.barcode.DMLTSConnectionParameters.sessionPassword
```

- **Value range**   
    Any string value   
      
- **Default value**   
    null


### deploymentType

Sets the deployment type.

```java
int com.dynamsoft.barcode.DMLTSConnectionParameters.deploymentType
```

- **Value range**   
    Any one of the [`EnumDMDeploymentType`]({{ site.enumerations }}other-enums.html#dm_deploymenttype) Enumeration items.   
      
- **Default value**   
    DM_DT_DESKTOP   
    
- **See also**  
    [`EnumDMDeploymentType`]({{ site.enumerations }}other-enums.html#dm_deploymenttype)    

### chargeWay

Sets the charge way.

```java
int com.dynamsoft.barcode.DMLTSConnectionParameters.chargeWay
```

- **Value range**   
    Any one of the [`EnumDMChargeWay`]({{ site.enumerations }}other-enums.html#dm_chargeWay) Enumeration items.   
      
- **Default value**   
    DM_CW_AUTO   
    
- **See also**  
    [`EnumDMChargeWay`]({{ site.enumerations }}other-enums.html#dm_chargeWay)    


### uuidGenerationMethod

Sets the method to generate UUID.

```java
int com.dynamsoft.barcode.DMLTSConnectionParameters.uuidGenerationMethod
```

- **Value range**   
    Any one of the [`EnumDMUUIDGenerationMethod`]({{ site.enumerations }}other-enums.html#dm_uuidgenerationmethod) Enumeration items.   
      
- **Default value**   
    DM_UUIDGM_RANDOM   
    
- **See also**  
    [`EnumDMUUIDGenerationMethod`]({{ site.enumerations }}other-enums.html#dm_uuidgenerationmethod)    

### maxBufferDays

Sets the max days to buffer the license info.

```java
int com.dynamsoft.barcode.DMLTSConnectionParameters.maxBufferDays
```

- **Value range**   
    [0,0x7fffffff]  
      
- **Default value**   
    0   
    

### limitedLicenseModules

Sets the license modules to use.

```java
int[] com.dynamsoft.barcode.DMLTSConnectionParameters.limitedLicenseModules
```

- **Value range**   
    Each array item can be any one of the [`EnumDMLicenseModule`]({{ site.enumerations }}other-enums.html#dm_licensemodule) Enumeration items.   
      
- **Default value**   
    null   
    
- **See also**  
    [`EnumDMLicenseModule`]({{ site.enumerations }}other-enums.html#dm_licensemodule)    
