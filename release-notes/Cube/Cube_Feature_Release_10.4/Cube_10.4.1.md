---
uid: Cube_Feature_Release_10.4.1
---

# DataMiner Cube Feature Release 10.4.1 – Preview

> [!IMPORTANT]
> We are still working on this release. Some release notes may still be modified or moved to a later release. Check back soon for updates!

> [!TIP]
> For release notes for this release that are not related to DataMiner Cube, see [General Feature Release 10.4.1](xref:General_Feature_Release_10.4.1).

## Highlights

*No highlights have been selected yet.*

## New features

*No new features have been added yet.*

## Changes

### Enhancements

#### Visual Overview: Enhanced service chain behavior [ID_37645]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

A number of UI enhancements have been made with regard to service chain behavior in visual overviews.

Up to now, in some cases, service chains could get redrawn too often, or shapes would not get redrawn when a service chain was updated. Also, context menus of shapes would not always close when those shapes were updated and context menus would incorrectly show the *Display connectivity* command twice.

#### Spectrum Analysis: Buttons in 'Reference lines' panel, 'Thresholds' panel and 'Measurement Points' panel have been restyled [ID_37752]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

In the *View* tab of a spectrum card, the buttons in the *Reference lines* panel and the *Thresholds* panel as well as the delete buttons in the *Measurement Points* panel have been restyled to match the buttons in the *Markers* panel.

### Fixes

#### Visual Overview: Placeholder containing '[Elapsed Time]' would not be updated when the elapsed time had changed [ID_37756]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

When the placeholder `[Elapsed Time]` was used inside another placeholder (e.g. `[Subtract:[Elapsed Time],[PreRoll]]`), the entire placeholder (e.g. `[Subtract:[Elapsed Time],[PreRoll]]`) would not be updated when the elapsed time had changed.

#### Relation learning: Problem when checking ModelHost DxM license [ID_37653]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

In some cases, DataMiner Cube could become unresponsive when checking the ModelHost DxM license.

#### Pattern matching: Memory leak [ID_37771]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

DataMiner Cube could start leaking memory when you opened trend graphs with pattern matching.

#### Data Display: Problem when hovering over lite parameter controls in Skyline Black theme [ID_37814]

<!-- MR 10.2.0 [CU22]/10.3.0 [CU10] - FR 10.4.1 -->

When DataMiner Cube was using the *Skyline Black* theme, lite parameter controls would become unreadable when you hovered over them.