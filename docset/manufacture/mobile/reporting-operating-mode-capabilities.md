---
Description: Reporting operating mode capabilities
MS-HAID: 'p\_phManuRetail.reporting\_operating\_mode\_capabilities'
MSHAttr: 'PreferredLib:/library/windows/hardware'
title: Reporting operating mode capabilities
---

# Reporting operating mode capabilities


If a Wi-Fi driver supports running in manufacturing mode, it should add manufacturing mode to its list of supported capabilities. You can query the supported operation mode capabilities by using the **OID\_DOT11\_OPERATION\_MODE\_CAPABILITY** command, which will return information on the operation modes supported by the driver. For more info about **OID\_DOT11\_OPERATION\_MODE\_CAPABILITY**, see [Supporting updated OID behavior in manufacturing mode](supporting-updated-oid-behavior-in-manufacturing-mode.md).

To switch the driver’s operation mode to manufacturing mode, use the **OID\_DOT11\_CURRENT\_OPERATION\_MODE** command to ensure that manufacturing testing will not conflict with the driver’s behavior in any of its other modes. For more info about **OID\_DOT11\_CURRENT\_OPERATION\_MODE**, see [Supporting updated OID behavior in manufacturing mode](supporting-updated-oid-behavior-in-manufacturing-mode.md).

## <span id="related_topics"></span>Related topics


[Adding Wi-Fi manufacturing test support to the OID interface](adding-wi-fi-manufacturing-test-support-to-the-oid-interface.md)

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_phManuRetail\p_phManuRetail%5D:%20Reporting%20operating%20mode%20capabilities%20%20RELEASE:%20%284/11/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



