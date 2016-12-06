This data repository belongs to the publication [**"Brown world forests: increased ungulate browsing keeps temperate trees in recruitment bottlenecks in resource hotspots"**](http://onlinelibrary.wiley.com/doi/10.1111/nph.14345/full) by Churski et al. New Phytologist.

#### Summary

* Consumers (mammalian herbivory and fire) are increasingly seen as major drivers of ecosystem structure and function but the prevailing paradigm in temperate forest ecology is still that their dynamics are mainly bottom-up resource-controlled. Using conceptual advances from savanna ecology, particularly the Demographic Bottleneck Model, we apply a novel view on temperate forest dynamics that integrates consumer and resource control.

* We use a fully factorial experiment, with varying levels of ungulate herbivory and resource (light) availability, to test how these factors shape recruitment of five temperate tree species. We ran simulations to project how inter- and intra-specific differences in height increment under the different experimental scenarios influence long-term recruitment of tree species. 

* Strong herbivore-driven demographic bottlenecks occurred in our temperate forest system, and bottlenecks were equally strong under resource-rich as under resource-poor conditions. Increased browsing by herbivores in resource-rich patches strongly counteracted the increased escape strength of saplings in these patches. 

* This finding is a crucial extension of the Demographic Bottleneck Model which assumes that increased resource availability allows plants to more easily escape consumer-driven bottlenecks. Our study demonstrates that a more dynamic understanding of consumer-resource interactions is necessary, where consumers and plants both respond to resource availability.

#### Data

Table **'browsing.csv'** contains data on browsed top shoots of the planted saplings inventored after one year from planting (yr 2009).

    Column headers description:

	'Site' : index for subsequent site (levels 1-6)
	'Gap': factor describing light tratment with two levels - Dark (Low Light) and Light (High Light)
	'Fence': factor describing herbivore treatment with two levels - Control (herbivores present) and Exclosure (herbivores
    excluded), here only Control treatment is present;
	'Species': factor describing species of the planted trees with 5 levels (Acer, Carpinus, Quercus, Picea, Tilia)
	'Available': variable describing sum of all available shoots for browsing per individual sapling;
	'Browsed': variable describing sum of all browsed shoots per individual sapling;

Table **'diameter.csv'** contains data on height (cm) and diameter (mm) measurements of the planted saplings inventored in year 2011

	Column headers description:

	'Site' : index for subsequent site (levels 1-6)
	'Gap': factor describing light tratment with two levels - Dark (Low Light) and Light (High Light)
	'Fence': factor describing herbivore treatment with two levels - Control (herbivores present) and Exclosure (herbivores excluded)
	'Species': factor describing species of the planted trees with 5 levels (Acer, Carpinus, Quercus, Picea, Tilia)
	'H11' : height measurements (cm) of the individual sapling in yr 2011
	'D11' : diameter (mm) measured at the base of the individual sapling in yr 2011

Table **'initial.csv'** contains data on the initial (yr 2008) height, diameter and main stem length measurements.

	Column headers description:

	'Site' : index for subsequent site (levels 1-6)
	'Gap': factor describing light tratment with two levels - Dark (Low Light) and Light (High Light)
	'Fence': factor describing herbivore treatment with two levels - Control (herbivores present) and Exclosure (herbivores excluded)
	'Species': factor describing species of the planted trees with 5 levels (Acer, Carpinus, Quercus, Picea, Tilia)
	'H8': height measurements (cm) of the individual sapling in yr 2008
	'S8' : main stem length measurements (cm) of the individual sapling in yr 2008
	'D8': diameter (mm) measured at the base of the individual sapling in yr 2008

Table **'survival.csv'** contains data on survived saplings after 5 years from planting (yr 2013). 

	Column headers description:

	'Site' : index for subsequent site (levels 1-6)
	'Gap': factor describing light tratment with two levels - Dark (Low Light) and Light (High Light)
	'Fence': factor describing herbivore treatment with two levels - Control (herbivores present) and Exclosure (herbivores excluded)
	'Species': factor describing species of the planted trees with 5 levels (Acer, Carpinus, Quercus, Picea, Tilia)
	'Survived' : binary variable indicating if the individual tree survived (1) or was dead (0).

Table **'trees.csv'** contains data on initial (yr 2008) and final (yr 2013) height measurements of the planted trees, based on which ANI was calculated.

	Column headers description:

	'Site' : index for subsequent site (levels 1-6)
	'Gap': factor describing light tratment with two levels - Dark (Low Light) and Light (High Light)
	'Fence': factor describing herbivore treatment with two levels - Control (herbivores present) and Exclosure (herbivores excluded)
	'Species': factor describing species of the planted trees with 5 levels (Acer, Carpinus, Quercus, Picea, Tilia)
	'H8': height measurements (cm) of the individual sapling in yr 2008
	'S8': main stem length measurements (cm) of the individual sapling in yr 2008
	'H13': height measurements (cm) of the individual sapling in yr 2013
	'S13': main stem length measurements (cm) of the individual sapling in yr 2013
