# anc-redistricting
work to gain early understanding of the ANC/SMD-level redistricting of Ward 5 in the District of Columbia

## background
The District of Columbia is split into eight wards. Each Ward is split into a variable number (4-7) of Advisory Neighborhood Commissions (ANCs) lettered A up to G, which are further split into a variable number ([2-12](https://twitter.com/ANCJonah/status/1444102088187908096?s=20)) of Single Member Districts (SMDs). ANCs are identified by Ward and letter (e.g. 5D for the nominally fourth of Ward 5) and SMDs are identified by ANC and SMD number (e.g. 5D03 for the third SMD within ANC 5D). The boundaries of all of these subdivisions are subject to change in response to each US Census.

Residents of SMDs elect ANC Commissioners who then serve within the SMD and on committee with the broader ANC. ANC Commissioner is a voluntary, unpaid, difficult, and important job. You can learn about it [here](https://anc.dc.gov/page/about-ancs) and [here](https://ggwash.org/view/43008/advisory-neighborhood-commissions-explained). Unfortunately, these positions often go vacant, or [worse](https://twitter.com/PritaPiekara/status/1445941469999730688?s=20).

2022 is a redistricting year. You can learn more about the redistricting process [here](https://planning.dc.gov/page/district-columbia-2021-ward-redistricting) and [here](https://dcist.com/story/21/05/25/as-d-c-kicks-off-redistricting-process-two-concerns-emerge-timing-and-parking/).

The TL;DR is:
- Ward-level districting is currently being debated and primarily concerns the contentious issue of shifting portions of Ward 6 into Wards 7 and 8.
- Population growth in Wards 1-5 is nontrivial, but tracks with the District as a whole, so significant Ward-level redistricting is unlikely.
- Ward-level redistricting will take a while, and only after that will ANC-level redistricting become a concern.
- ANCs are nonpartisan offices not subject to a primary, so ANC candidate sign-up only becomes a hard deadline in summer 2022. We might not know the final boundaries until then.

## purpose
The purpose of this repository is to explore available data and begin forming an understanding of the redistricting concerns communities will likely have. The scope may grow and shrink over time.

Initially, the plan is to crunch the ANC- and SMD-level populations for pre-2022 boundaries to identify imbalances created by the [2020 Census numbers](https://planning.dc.gov/publication/2020-census-information-and-data). Any code artifacts will live in this Github repo for now.

## data sources
All data is from [OpenDataDC](https://opendata.dc.gov) and must be downloaded as geojson placed in a `data` directory within the repo
- [SMDs from 2013](https://opendata.dc.gov/datasets/DCGIS::single-member-district-from-2013/about)
- [Census Blocks from 2010](https://opendata.dc.gov/datasets/DCGIS::census-blocks-in-2010/about)
- [Census Blocks from 2020](https://opendata.dc.gov/datasets/DCGIS::census-blocks-in-2020/about)
