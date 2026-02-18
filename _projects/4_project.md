---
layout: page
title: Household Archetypes
description: Typical household profiles by demographics and consumption.
img: assets/img/projects/household_archetypes/archetype_breakdown.png
importance: 1
category: work
---

**Household Profiles (Archetypes)** is a CBEI dashboard page that breaks down a region’s households into a small set of typical profiles (e.g. 5–8 clusters) using **k-means clustering** on demographics and consumption, then shows how each profile contributes to consumption-based emissions. It uses state-level archetype data (demographics, emissions by category) and, for counties, county-level shares and PUMA-level distributions.

The page answers: *What kinds of households live here, how do they differ in emissions, and where (by PUMA) do different profiles concentrate?* so users can target policies and outreach by household type and geography. The frontend has four tabs—Overview (PUMA map, demographic cards, profile vs state average), Impact (total emissions by profile), Drivers (emissions by category per profile), and PUMA Breakdown (profile mix by area)—plus filters and detailed tables.

The views below are a selected sample; the full Household Archetypes dashboard has more charts, tabs, and filtering.

<div class="row">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/household_archetypes/archetype_breakdown.png" title="Archetype breakdown" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/household_archetypes/archetype_emissions.png" title="Emissions by archetype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/household_archetypes/archetype_total_emissions.png" title="Total emissions" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Selected views from the Household Archetypes dashboard—profile breakdown, emissions by archetype, and total emissions.
</div>
