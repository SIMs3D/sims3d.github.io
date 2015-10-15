---
layout: page
title: Research line 2 
---

## Smart spatial space subdivision for indoor navigation

<div class="row">
  <div class="col-sm-12 hidden-xs nopadding"><img class="img-responsive" src="{{ "img/rl2.png" | prepend: site.baseurl }}"></div>
</div>

- - -
<div align="justify">

To be able to provide navigation and guidance, the models (geometry and semantics) have to be enhanced with connectivity information, i.e. a network has to be created. One approach to create such a network is to apply
Poincaré Duality, according to which each node represents a space and an edge depicts the (connectivity) link between spaces (Becker et al., 2008; Lee, 2004; Lee and Zlatanova, 2008). This concept is central for IndoorGML,
an OGC candidate standard (http://www.opengeospatial.org/projects/groups/indoorgmlswg). By changing the space subdivision, different networks can be created completely automatically. The semantics and the
properties attached to the geometric spaces can be propagated to the nodes and the edges of the network. 

<br> <br>

Another interesting approach is to use a 3D combinatorial map (3-map) for the description of the connectivity between the elements of the described buildings (Damiand et al. 2015). 
That data structure has been successfully used to describe geometry, topology and semantic information all combined for 3D building models (Diakité et. al, 2014). 
It stands as a bridge between complex models (IFC and CityGML) and applications (simulation, building analysis, etc). By exploring the operations 
and the formalism offered by the 3-maps, it is possible to model the buildings in a convenient way to perform a generic space subdivision approach, 
that is suitable for automatic extraction of adaptive navigation routes.

<br> <br>

Space can be subdivided using different geometric or semantic criteria or combinations of them (Afyouni et al.,2012). For example, Khan and Kolbe (2013) provide an approach for space subdivision, which considers the
locomotion types of humans (walk, drive). We will follow an approach making use of user perception of space (Hall, 1969; Junestrand et al., 2001; Nakauchi
and Simmons, 2002; Scheflen, 1975) and ‘attractiveness’ of objects of interest. We have developed a framework in which we distinguish between agents (humans and human proxies), which perform actions to approach
resources. The agents, actions and resource can be affected by modifies (i.e. events that modify the status of any of the three). Modifies can be emergencies such as a fire or smoke (Zlatanova et al., 2013). Our initial
investigations have shown that resources can hold a number of characteristics (function, attractiveness, time, accessibility, number of agents, social distance, etc.). These properties are used to assign a space around the
resources, which can be used for localization of agents but cannot be used to navigate other agents through. These spaces delineate the possible navigable space (i.e. the spaces which are outside the spaces for resources). By developing a proper grammar to utilize these criteria, we can change the spaces around resources dynamically. For example, the area around a coffee corner can be several meters during coffee break
and only a meter outside.

</div>

## Contacts

- Abdoulaye Diakité (<diakite.abdoulaye@live.fr>)
- Sisi Zlatanova (<s.zlatanova@tudelft.nl>)
