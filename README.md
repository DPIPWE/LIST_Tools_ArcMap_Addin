## News
* **Oct 2019. Release 7 v3.01.01.  Previous versions of this software are no longer compatible with theLIST  as of 15 Oct 2019.**

* **May 2021. Release 9 v3.03.00** is the last release compatible with ArcMap 10.6. It can be run by ArcMap 10.8 but will not run on latter versions of ArcMap

* **May 2021. Latest release, 10 v4.01.0** targets ArcMap 10.8. Is is not backward compatible to say ArcMap 10.6

* **March 2022. Changes to documentation** to reflect organization name change from Dpartment of Primary Industries Water Environment (DPIWE) to Natural Resources Environment Tasmania (NRE). 


# DPIPWE_Tools_Addin

This ESRI Addin toolbar, for ArcMap provides access to a variety of web based services: theLIST, Google Earth and ArcGIS Online. These services are focused on the Australian state of Tasmania. This Addin is provided by [Land Tasmania](http://nre.tas.gov.au/land-tasmania).

[**TheLIST**](https://www.thelist.tas.gov.au/app/content/home)  is a contemporary online service that provides access to integrated land and property information service. [LISTMap](https://maps.thelist.tas.gov.au/listmap/app/list/map) allows users to view and create maps from hundreds of authoritative spatial datasets, and find out more about the information shown on those maps.

Spatial datasets include natural resources, roads, community facilities, property boundaries (cadastre), aerial imagery and survey information.

LISTMap is publicly available through your computer's web browser or via your mobile device.

The DPIPWE_Tools_Addin has single click buttons for loading either the Tasmanian colour topographic base-map, or the state-wide ortho-photo mosaic from LISTMap into ArcMap. The user can also link to other LIST web services via ArcMap’s catalogue. A view of LISTMap with a similar extent as your current ArcMap extent can be loaded into your browser. A version of the LISTMap search service is provided that finds and highlights feature.

For more detailed information on how to access LIST web services, see the following [LIST spatial web services users guide](https://www.thelist.tas.gov.au/app/content/the-list/news_and_information/resources/list_spatial_web_services_user_guide.pdf)

**Google Earth** on your PC can be invoked with a view that matches the current ArcMap frame extent.

Connect to **ArcGIS Online** public data with a single button click.

## How to get the addin

* Download the [latest release](https://github.com/DPIPWE/DPIPWE_Tools_Addin/releases/latest) (targets ArcMap 10.8) or the earlier [v3.03.00](https://github.com/DPIPWE/DPIPWE_Tools_Addin/releases/tag/v3.03.00) release for ArcMap 10.6.
* UnZip the archive

* Place the *.esriAddin file in your preferred directory

* Configure ArcMap Add-In Manager.

Detailed installation instructions are given in the **_user guide_**. found in the documentation folder.


## Documentation
This readme is designed to be a general introduction to the tool. Within the *docs* folder there is;

* ReleaseNotes_DPIPWE_tools.pdf , *notes for each release, with details about compatibility, installation, known limitations ...*

* UserGuide_DPIPWE_tools.pdf , *detailed guide of how to use the tools*.

## History

The ESRI-Addin presented here was created within the GIS Systems and Development (Spatial Operations) section of the [Heritage and Land Tasmania](http://nre.tas.gov.au/land-tasmania) Division within the Department [Natural Resources and Environment](http://nre.tas.gov.au/) Tasmania (formally Primary Industries Parks Water and Environment DPIPWE) in the state government of Tasmania, Australia. In the course of our support for internal clients we have developed several ArcMap tools. These have been gathered together onto a single ESRI toolbar Addin. After being tested and used within the Spatial Operations section, this Addin was first  released to NRE/DPIPWE in 2015. It was first released to the wider community via this GitHub account in July 2016.

Release 8 v3.01.02, now targets ArcMap 10.6 rather than 10.3, and has been updated to match theLIST service changes introduced on 15 Oct 2019. Previous versions are now incompatible with theLIST. 

Release 9 (2021) v3.03.00 is the last compatible with ArcMap 10.6. It can be run on ArcMap 10.8. It can not be run with ArcMap beyond 10.8.

Release 10 (2021) v4.01.00 targets ArcMap 10.8 and is not backward compatible with earlier versions of ArcMap.

## Development

DPIPWE_Tools_Addin now targets ESRI ArcMap 10.8, for the .Net 4.5.2 framework under the Windows 10 operating system. The code is written in VB.Net with ArcObjects SDK for .Net from ESRI using Visual Studio 2017. 

## Limitations / Known issues
After the Aug 2019 release, the Google Earth View command works with any relase of Google Earth that can be sucessfully installed. This removes the restriction of using an old version of Google Earth.  See the User Notes.

Previous versions of this software are no longer compatible with [**LISTmap**](https://maps.thelist.tas.gov.au/listmap/app/list/map) as of 15 Oct 2019. TheLIST no longer supplies Image Services. The orthophoto and topograpic basemaps were previously consumed as image services.

## Disclaimer

DPIPWE_Tools_Addin is released to the wider community “as-is”. Although our testing and usage has been extensive, this experience has been with a limited number of different computer environments. Thus we cannot guarantee in any way that it will work the same way in your environment. Bear in mind that these tools have been developed primarily for internal NRE staff, and hence our ability to provide support to external users is limited.

## Contact

**Spatial Operations**

134 Macquarie Street

HOBART TAS 7000

Phone (03) 6165 4118

Email mailto:gissd@dpipwe.tas.gov.au 

<img src="media/Tas_Gov_logo.jpg" width="300" height="108" />
