---
layout: page
title: Research line 1 
---

## Reconstruction of semantically rich 3D building models from point clouds

<div class="row">
  <div class="col-sm-12 hidden-xs nopadding"><img class="img-responsive" src="{{ "img/1.png" | prepend: site.baseurl }}"></div>
</div>

<div align="justify">

This research line aims at developing a shape grammar for (semi-) automated generation of semantically-rich 3D models of
indoor environments from large point clouds. Indoor architecture is characterized with three elements: repetition, regularity and creativity. Regular structures
like cuboid spaces repeatedly appear in indoor environments but in very many different configurations reflecting
the creativity of the architect. A design principle that combines these elements and explains their working in
architecture is the shape grammar. It establishes that different designs can be made by iteratively applying
grammar rules to simple shapes. By choosing different shape parameters and varying the sequence
of rules many different creative designs can be created. Shape parameters also contain semantics of spaces such
as the height of walls, ceilings, floors, doors and windows.

<br> <br>

For the 3D modelling of interior spaces we will define a parametric shape grammar similar to the Palladian
grammar, which has been used to describe Palladian style indoor designs. It consists
of a starting shape and a set of rules that are iteratively applied to the starting shape to produce intermediate
shapes and eventually the final spaces of the interior. We use a parameterized cube of unit size as the starting
shape as it represents a 3D subspace. The rules can then change the size of the unit cube, place it in certain
positions and merge multiple cuboid to form more complex interior spaces. The advantage of shape grammar over similar
methods, e.g. split grammar, is that it is based on an architectural indoor design
concept and is therefore better suited for modeling indoor spaces. In addition, the shape parameters are part
of the required semantics and can be directly used in optimal path finding.

<br> <br>

We will develop and extend the shape grammar to enable modelling of complex indoor environments up to the
level of details required for optimal routing and navigation. We will augment the grammar
with semantic rules, which makes it possible to extract and add semantics to the reconstructed spaces. Any
object that is not part of the interior structure of the building will be classified as clutter and further to different
types of furniture. We will also develop methods to learn the sequence and parameters of the grammar rules
from the point cloud. Our preliminary experiments show that the distribution of points in the point cloud
provides information on the position of the main structural elements, and can be used to estimate the
parameters of the grammar rules. Although we aim to minimize user interaction by learning the grammar from the data, 
in the implementation we will develop software tools that allow and facilitate user interaction to correct or modify the procedure and the models.

</div>


## Contacts

- Shayan Nikoohemat (<s.nikoohemat@utwente.nl>)
- Michael Peter (<m.s.peter@utwente.nl>)
- George Vosselman (<george.vosselman@utwente.nl>)
