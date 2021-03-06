---
title: LevelSaveData
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[LevelSaveData](#constructor-0)**() |
| **[LevelSaveData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[LevelSaveData](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "saveSize" >}} | int |
| {{< prop "saveNames" >}} | string[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "LevelSaveData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### LevelSaveData {#constructor-0}

> **LevelSaveData**()

Creates a new [LevelSaveData](/vext/ref/fb/levelsavedata) frostbite instance.

### LevelSaveData {#constructor-1}

> **LevelSaveData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [LevelSaveData](/vext/ref/fb/levelsavedata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### LevelSaveData {#constructor-2}

> **LevelSaveData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [LevelSaveData](/vext/ref/fb/levelsavedata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [LevelSaveData](/vext/ref/fb/levelsavedata). |

## Properties

### {{% prop-heading "saveSize" %}}

> **int**

### {{% prop-heading "saveNames" %}}

> **string**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [LevelSaveData](/vext/ref/fb/levelsavedata) type.

