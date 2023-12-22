---
layout: page
title: Aerosols in climate policy
description: How aerosols change decisions and outcomes around climate policy
img: assets/img/Smoke_thumbnail.jpg
importance: 3
category: work
---

Climate policy will change air pollution because climate pollutants and traditional pollutants are often co-emitted when burning fossil fuels. Cleaner air is an immediate and local benefit of changing emissions, which is fundamentally different from the impacts of climate change that tend to be long-term and spatially diffuse. Changes to air pollution are often not considered when modeling climate policy decisions, even though they come up in local and international policy documents. Furthermore, those particulates (aerosols) have their own climate impacts. A very general way to think about decisions and feedbacks is shown below.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Decision_FlowChart.png" title="Global stations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We implemented highly idealized decision criteria that incorporate the health and climate impacts of aerosols in theoretical implementations of countries' Paris Agreement emission reduction targets. We showed that considering aerosols as part of climate policy can be objectively beneficial in some cases. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/GlobalT_vs_Mortality.png" title="Global stations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Health and climate outcomes from aerosols using three different idealized decision criteria. Top right is objecively worse that bottom left. In some regions the "equal" priority is objectively worse than the others.
</div>

We used a similar approach in a US-specific study that explores the equity outcomes of different idealized climate policy implementations. But these studies still do not interactively consider the feedbacks between decisions and outcomes. Modeling those interactions is a job for an integrated assessment model (IAM), which explicity couples human and natural systems. I am currently working on improving one such model and including aerosol health and climate impacts.

In an early attempt to think about the connection between human institutions and distribution of impacts, I used regressions to model the climate impacts of OECD and non-OECD aerosols. 

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/OECD_nonOECD_summary.png" title="Global stations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Temperature change caused by aerosols from two different regions according to regressions on CESM2 aerosol-only simulations. 
</div>

I think this is pretty cool! But there's a lot left to do and I'm actively working on it with others in the Ricke group. The regional impacts of aerosols could definitely have geopolitical implications, especially if altered intentially.

