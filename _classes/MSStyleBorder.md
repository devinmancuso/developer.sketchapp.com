---
title: MSStyleBorder
summary: Represents a border on a layer. Can be either a color or gradient fill.
rels:
  - MSStyle
  - MSGradient
  - MSStyleFill
---

Represents a border on a layer. Can be either a color or gradient fill.

## Methods & Attributes

### position

The position of the layer; Center (0), Inside (1) or Outside (2).

### thickness

The thickness of the border as a float value.

### fillType

A color fill (0) or a gradient (1). Other values make no sense and can lead to unpredictable behaviour.

### gradient

An [MSGradient](/reference/class/MSGradient/) object that will only be used if the `fillType` is set to a gradient.

### isEnabled

Whether the style object is enabled or not
