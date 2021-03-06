
# Cityscapes Panoptic Parts annotations
We have manually annotated 5 scene-level classes with 23 part-level classes from Cityscapes vehicle and human categories.

Pixels of humans and vehicles (_sids_: 24, 25, 26, 27, or 28) that are not assigned to any part-level class by the annotation team or it is not clearly visible to which part they belong to, have _pid_ = 0 or they maintain their semantic-level or semantic-instance-level labels. From the perspective of semantics the labels `SS_III_00` and `SS_III` are equivalent.

## Human (person (_sid_: 24), rider (_sid_: 25)) pids:
* 0: unlabeled / void
* 1: torso
* 2: head
* 3: arms
* 4: legs

## Vehicle (car (_sid_: 26), truck (_sid_: 27), bus (_sid_: 28)) pids:
* 0: unlabeled / void
* 1: windows
* 2: wheels
* 3: lights
* 4: license plate
* 5: chassis
