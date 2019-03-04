---
layout: page
title: About
permalink: /about/
---

I am currently an Independent Consultant for Imperial College London, and will shortly become a Project Manager (again) managing the RIF development. I will also leading on the front end, any database work needed and help to integrate the RIF into the [Small Area Health Statistics Unit](http://www.sahsu.org)'s  network.

# My Career

I completed a B.Eng (2:1) in Electrical and Electronics Engineering from Imperial College London in 1989 and then spent five years with BT research and firve years with [ABS](https://www.abs5.co.uk/). After a five month contract for [Amadeus](https://amadeus.com/en) I then worked from 2012 until the end of 2016 as the Projects Manager and Database Administrator for UK Small Area Health Statistics Unit or [SAHSU](http://www.sahsu.org) at the Department of Epidemiology and Biostatistics, Imperial College London.

## Recent work

For the past three years I have been working on the [Rapid Inquiry Facility](http://www.sahsu.org/content/rapid-inquiry-facility) or RIF. The RIF is a sophisticated software tool for environmental public health risk assessment, and was rewritten in Angular 1.x and Leaflet with Java middleware. The source code is the Github  [rapidInquiryFacility](https://github.com/smallAreaHealthStatisticsUnit/rapidInquiryFacility) project. I have built the RIF to support both SQL Server and PostgreSQL databases. I extensively re-designed the RIF database inherited from my SAHSU Database Manager years (see below) to be data driven by the extraction of study data, followed by its statistical processing (in R). My redesign emphasized performance, scalability, security and modularity. The new RIF can extract data in minutes compared to hours in the previous version. The RIF project is a collaboration with the [US Centers for Disease Control, in their Environmental Public Health Tracking Program](http://www.cdc.gov/nceh/tracking/).

I have provided consultancy as required on the project and have carried out the following:

*	Generate the TopoJSON tiles required by the front end using a JQuery-UI front end with Node.js middleware. This loaded the shapefiles, converting the geometry to WGS84 (GPS) projection, simplified the GeoJSON to TopoJSON and created the data and database scripts for further database processing. The database phase cleaned the simplified data, created a hierarchy of intersections between the different levels of administrative geography, created GeoJSON intersections for the tiles and the adjacencies required for Bayesian smoothing;
*	Created the *markdown* installation documentation. I also made numerous changes to the middleware and front end to make the software easy to install, configure and upgrade and also to improve the logging and exception handling;
*	Added map creation facilities to the Java middleware by the addition of REST services. The extract also contains shapefiles and styling documents to allow the user to re-create maps in GIS software;
*	Modified the Angular front end to add additional modal windows, principally to support the Risk Analysis functionality in the RIF;
*	Improved the performance of the Angular front end and the Java middleware to cope with very large database sets (e.g. 227K UK census output areas). Added support for on the fly generation of PNG tiles from TopoJSON with a thread to pre-create tiles for common map zoomlevels (6-9);
*	Developed a Leaflet TopoJSON GeoJSON GridLayer plugin. This includes local disk caching of map tile TopoJSON.

## Publications

I am not an academic, and am normally acknowledged and thanks on papers; however I have picked up a few over the years - normally where data preparation was unusually important to the paper.

*	Toledano MB; Nieuwenhuijsen MJ; Best N; Whitaker H; Hambly P; de Hoogh C; Fawell J; Järup L; Elliott P. (2005) Relation of trihalomethane concentrations in public water supplies to stillbirth and birth weight in three water regions in England. Environ Health Perspectives. 113: 225-232;
*	Hodgson, Susa; Beale, Linda; Hambly, Peter; Parslow, Roger C; Feltbower, Richard G; Jarup, Lars. (2011). Creating a National Register of Childhood Type 1 Diabetes Using Routinely Collected Hospital Data. Epidemiology: January 2011 - Volume 22 - Issue 1 - pp S279-S280;
*	Perviz Asaria, Lea Fortunato, Daniela Fecht, Ioanna Tzoulaki, Juan Jose Abellan, Peter Hambly, Kees de Hoogh, Majid Ezzati, and Paul Elliott (2011). Trends and inequalities in cardiovascular disease mortality across 7932 English electoral wards, 1982–2006: Bayesian spatial analysis. International Journal of Epidemiology. 2012 December; 41(6): 1737–1749;
*	Federico Fabbri; Yang Wang; Peter Hambly; Linda Beale; Anna Hansell; (2012) The Redevelopment of the Rapid Inquiry Facility Tool for Environmental Epidemiological Analysis. Epidemiology 23(5S):1;
*	Bennett JE; Li G; Foreman K; Best N; Kontis V; Pearson C, Hambly P, Ezzati (2015) The future of life expectancy and life expectancy inequalities in England and Wales: Bayesian spatiotemporal forecasting. Lancet. 2015 Jul 11; 386(9989):163-70.

### Contact me

[peterblog@fastmail.co.uk](mailto:peterblog@fastmail.co.uk)
