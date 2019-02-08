# project-universal-stationID
This repo houses project discussions for creating a universal station ID system.

*Comments at any time are welcome, but for consideration of incorporation into this project, please provide input by **February 15, 2019***.

## 1. Background on the Problem This Project Addresses

[OpenAQ](https://openaq.org) aggregates air quality data from disparate governmental and research sources across the world and harmonizes them into one consistent [data format](https://github.com/openaq/openaq-data-format). 

As displayed [here](https://github.com/openaq/openaq-data-format), the data format includes a parameter called `location`, which is the unique station name _as designated by the originating data source_. This means, if a source calls a station location "A" today, but tomorrow decides to change the name to "B," this change will dynamically be reflected in our system. While this method of handling ``location`` allows for transparency and gives the originating data source control of how the name of the station appears in our system, without a persistent ``stationID``, there can be confusion about these station name changes.

Feedback from the OpenAQ Community has made clear that there is a desire for a persistent and universal ``stationID`` to be associated with the measurements in the OpenAQ system. This project seeks to address this issue. 


## 2. Project Purpose and Description

To address the problem outlined above, OpenAQ, along with our partners and the broader OpenAQ Community, are creating a Station ID system and then applying that system to the data in the OpenAQ platform. 

Another piece of this project is building a metadata editor and discerning what metadata are most useful to collect and share with the community. Please see [this related GitHub repo](https://github.com/openaq/project-metadata-format) for more information.


## 3. Call for Community Input on a Universal Station ID System for the OpenAQ Platform

We are seeking input from the community on the creation of this Station ID System. All input provided may not be able to be included in the final output of this specific project for a variety of reasons, but input from as broad a swath of the OpenAQ Community as possible is valuable to the short term of this project and in the longer term for others' benefit and the platform in the future.


### **If you are interested in contributing comments on the Station ID system, please make an "Issue" in this repo by February 15, 2019. You can read more [here](https://github.com/openaq/project-universal-stationID/issues/1#issue-404988531) on how to do this.** 

This will require that you have a GitHub Account. If you prefer not to use GitHub, please send your input to info@openaq.org, and we will make an issue on your behalf, including your name and affiliation, as available and unless otherwise instructed to not do so. 

If you are interested in providing input on another related project, focused on building a universal station ID system, please see [this related GitHub repo](https://github.com/openaq/project-metadata-format) for more information.


## 4. Sponsors and Partners in this Work

This work is sponsored by the IntelliAQ Team at [Forschungszentrum Jülich GmbH](http://www.fz-juelich.de/portal/DE/Home/home_node.html) through a grant from the European Research Council: ERC-2017-ADG #787576. [Development Seed](https://developmentseed.org/) is constructing the Station ID system and implementing it. As always, the larger OpenAQ Community is also providing key input to shape the project in the ways that best support their diverse and impactful air inequality works.

For reference, other sponsors of OpenAQ are listed [here](https://openaq.org/#/about).



