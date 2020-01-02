---
title: RoundEvent
---
### Base Classes

[MetricEvent](MetricEvent)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| RoundEvent()                                                          | Create a new instance of this container type.                                                               |
| RoundEvent(RoundEvent other)                                          | Create a reference copy of an instance of the same type.                                                    |
| RoundEvent([MetricEvent](MetricEvent) other)                          | Upcast an instance of type [MetricEvent](MetricEvent) to [RoundEvent](RoundEvent).                          |
| RoundEvent([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [RoundEvent](RoundEvent). |

## Properties

| Name           | Type   | Description |
| -------------- | ------ | ----------- |
| levelName      | string |             |
| juiceSessionId | number |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [RoundEvent](RoundEvent) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [RoundEvent](RoundEvent) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |