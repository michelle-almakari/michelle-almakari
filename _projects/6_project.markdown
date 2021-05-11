---
layout: page
title: Non-linear wave propagation 
longtitle: Saturation of surface PGA with non-linear wave propagation
description: in collaboration with Pierre-Yves Bard (ISTerre), Bertrand Guiller (ISTerre) and Christelle Salameh (ISTerre).
time: First year Master project
img: /assets/img/Surface_PGA.png
importance: 4
category: past
---
Under seismic loading, when the shear strain increases, the soil profile goes farther and farther into the non-linear domain especially in the weakest layer, the corresponding shear stress is getting nearer and nearer to its asymptotic value τmax, and cannot transmit accelerations higher than (approximately) τmax / ρ. z, where ρ is the unit mass and z the depth of the considered layer. As a consequence, at each site, the peak surface acceleration cannot exceed the threshold value corresponding to its weakest layer where the higher strains are developed. \
Here we conducted a numerical modeling study of non-linear wave propagation for 820 multilayered soil profiles (593 Japanese KiK-net sites, 205 sites from the US and 22 European sites from theNERIES project) and 60 synthetic input accelerograms (realistic waveforms presenting both frequency and non-stationary characteristics representative of real accelerograms, corresponding to scenario earthquakes with a magnitude range from 3 to 7, recorded at distances from 2 to 100 km). \
This "saturation" value of pga appears very clearly with the variation of surface pga with peak strain. For a given site, low input pga values generate small peak strain within the soil profile, which remains well below the corresponding "reference strain" γref = τmax / Gmax (where Gmax is the low strain shear modulus at the depth of the peak strain). When the input pga increases, the peak strain γmax keeps increasing, and when it gets comparable to or higher than γref, the soil goes far into the non- linear domain, and the transmitted acceleration gets close to its saturation value. This explains the asymptotic shape of curves, which also indicates that the saturation pga is decreasing with decreasing soil stiffness : the lowest saturation pga (around 2 m/s2) correspond to red points, i.e. those with VS30 < 180 m/s, while the largest (around 7 m/s2) correspond to magenta points i.e. with VS30 > 760 m/s.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/Surface_PGA.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
Saturation of the surface PGA for different VS30 site classes. One point in this graph represents the surface pga as a function of peak "relative strain" (ratio γmax/γref where γmax is the peak strain value along the whole profile and γref is the reference strain at the corresponding depth). 
</div>
