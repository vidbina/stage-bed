# Stage Bed :metal:

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

This is frame for the bed that
[@lenipaperboats](https://instagram.com/lenipaperboats) and I built. The
panelling work is not included in these drafts. The design objective was to
create a bed that we could double as a set for photoshoots or a stage for
pillow fights or bedroom concerts :sunglasses:.

![Preview of the bed model when composed](./docs/model-preview.png)

A [plan][plan] of the components required is provided in [docs/plan.pdf][plan]
## Parameters

The Dimensions table contains some parameters that can be modified to change
the dimensions of the model.

> Some components may require repositioning if values in this table are
> modified.

| Section | Dimension | Description |
|----|----|----|
| `Mattress` | `length` | Length of the mattress|
| `Mattress` | `width` | Width of the mattress|
| `Mattress` | `height` | Height of the mattress|
| `Mattress` | `radius` | Radius in the rounding of the mattress corners|
| `Slat supports` | `Slat width` | Width of one the edge slat of the Lattenrost | 
| `Slat supports` | `Slat height` | Height of the one edge slat of the Lattenrost |
| `Slat supports` | `slat_foundation_side` | Width of the support that carries the slats of the Lattenrost |
| `Beams` | `width` | Width of the beams used to create the top-facing support lattice |
| `Beams` | `height` | Height of the beams used to create the top-facing support lattice |
| `Beams` | `groove` | Height of the groove used to interlock the beams in the top-facing support lattice |
| `Loadbearer` | `length` | Length of the beams used for top-facing surface |
| `Loadbearer` | `height` | Height of the beams used for the top-facing surface (same as `Beams` / `height`) |
| `Loadbearer` | `width` | Width of the beams used for the top-facing surface (same as `Beams` / `width`) |
| `Pillars` | `height` | I dunno :shrug: |
| | `seat_height` | The height of the sitting surface |
| | `seat_width` | The width of the sitting edge around the mattress |

[plan]: ./docs/plan.pdf
