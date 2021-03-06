---
title: SupportedShootingBinding
---

## Summary

### Constructors

|  |
| --- |
| **[SupportedShootingBinding](#constructor-0)**() |
| **[SupportedShootingBinding](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "supported" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "supportedPos" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "forwardVector" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "yaw" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "pitch" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "distToObject" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "heightOfObject" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "undeploying" >}} | [AntRef](/vext/ref/fb/antref) |
| {{< prop "animatedCamera" >}} | [AntRef](/vext/ref/fb/antref) |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "SupportedShootingBinding" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### SupportedShootingBinding {#constructor-0}

> **SupportedShootingBinding**()

Creates a new [SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding) frostbite instance.

### SupportedShootingBinding {#constructor-1}

> **SupportedShootingBinding**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "supported" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "supportedPos" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "forwardVector" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "yaw" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "pitch" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "distToObject" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "heightOfObject" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "undeploying" %}}

> **[AntRef](/vext/ref/fb/antref)**

### {{% prop-heading "animatedCamera" %}}

> **[AntRef](/vext/ref/fb/antref)**

## Methods

### Clone {#clone}

> **Clone**(): [SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [SupportedShootingBinding](/vext/ref/fb/supportedshootingbinding) type.

