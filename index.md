---
layout: media
permalink: /
image:
  feature: "seismic_banner.png"

#excerpt: "Be patient - the project is just bootstrapping..."
#title: "Next generation subsurface imaging software"

---

**Open Performance portablE SeismiC Imaging (OPESCI)** is a framework for
subsurface imaging. Its development focus on exploiting modern trends in
computer science and numerical analysis to achieve performance portability
across modern many-core computer architectures while maintaining a high level
abstraction that allows rapid research, development and deployment. 

**Research themes**

* Stencil languages, domain specific languages (DSLs) for finite difference.
* DSLs for finite element methods and spectral element methods.
* Code generation, autotuning and compiler research.
* Automatic differentiation.
* Parallel algorithms.
* Multi-layered abstractions and performance portability.

Wherever possible we use other open source components as building blocks.
Projects we are collaborating on include:

* [Firedrake](http://www.firedrakeproject.org)
* [FInAT](https://github.com/FInAT/FInAT)
* [PRAgMaTIc](https://github.com/ggorman/pragmatic)

**Partners**

This initiative the focus of an [Intel Parallel Computing Center](https://software.intel.com/en-us/ipcc) in partnership with [BG Group](http://www.bg-group.com/) in Brazil. It is a collaborative project between researchers [Imperial College London](http://www.imperial.ac.uk) and [SENAI CIMATEC](http://portais.fieb.org.br/senai/senai-na-sua-cidade/salvador/cimatec.html).

**Contact**

Feel free to get involved via GitHub or by <a href="mailto:g.gorman@imperial.ac.uk;renato.miceli@fieb.org.br?Subject=[PESCI-web] contact" target="_top">emailing us directly</a> for further details.

<table>
<tr>
<th><a href="http://www.imperial.ac.uk"><img src="/images/logo_imperial_college_london.png" style="max-height:100px"></a></th>
<th><a href="http://portais.fieb.org.br/senai/senai-na-sua-cidade/salvador/cimatec.html"><img src="/images/logo_senai_cimatec.jpg" style="max-height:100px"></a></th>
</tr>
<tr> 
<th><a href="http://www.intel.com"><img src="/images/IntelLogo.png"></a></th>
<th><a href="http://www.intel.com"><img src="/images/XeonPhiLogo1.png"></a></th>
</tr>
<tr>
<th><a href="http://www.bg-group.com"><img src="/images/BGGroupLogo.png"></a></th>
</tr>
</table>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
