---
title: SoldierHealthModuleData
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                        | Description                                                                                                                           |
| ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| SoldierHealthModuleData()                                                          | Create a new instance of this container type.                                                                                         |
| SoldierHealthModuleData(SoldierHealthModuleData other)                             | Create a reference copy of an instance of the same type.                                                                              |
| SoldierHealthModuleData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SoldierHealthModuleData](SoldierHealthModuleData). |

## Methods

| Type                                               | Name            | Parameters                                     |
| -------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SoldierHealthModuleData](SoldierHealthModuleData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SoldierHealthModuleData](SoldierHealthModuleData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |