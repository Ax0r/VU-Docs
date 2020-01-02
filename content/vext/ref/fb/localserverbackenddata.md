---
title: LocalServerBackendData
---
### Base Classes

[ServerBackendData](ServerBackendData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                       | Description                                                                                                                         |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| LocalServerBackendData()                                                          | Create a new instance of this container type.                                                                                       |
| LocalServerBackendData(LocalServerBackendData other)                              | Create a reference copy of an instance of the same type.                                                                            |
| LocalServerBackendData([ServerBackendData](ServerBackendData) other)              | Upcast an instance of type [ServerBackendData](ServerBackendData) to [LocalServerBackendData](LocalServerBackendData).              |
| LocalServerBackendData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [LocalServerBackendData](LocalServerBackendData).                                      |
| LocalServerBackendData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [LocalServerBackendData](LocalServerBackendData). |

## Methods

| Type                                             | Name            | Parameters                                     |
| ------------------------------------------------ | --------------- | ---------------------------------------------- |
| [LocalServerBackendData](LocalServerBackendData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [LocalServerBackendData](LocalServerBackendData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |