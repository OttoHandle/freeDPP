The project aims to support anyone implementing the mandatory Digital Product Passport Service according European Sustainability for Products Regulation 1781/2024
Implementing shall be done according forthcoming CEN/CENELEC Standards 

     EN 18219 DPP - Unique identifiers 
     EN 18220 DPP - Data carriers 
     EN 18239 DPP - access rights management, information system security, and business confidentiality 
     EN 18223 DPP - System interoperability EN 18216 DPP - Data exchange protocols 
     EN 18221 DPP - data storage, archiving, and data persistence 
     EN 18246 DPP – Data authentication, reliability and integrity   
     EN 18222 DPP - Application Programming Interfaces (APIs) for the product passport lifecycle management and searchability 

Note:
-----
Project starts on April 1st 2026, when european standards for the digital product passport are published.
Edit 26-06-20:
In May 28th, 2026 six of the eight standards have been published and can be purchased (currently only in english language) here:
https://standards.cencenelec.eu/ords/f?p=205:32:::::FSP_ORG_ID,FSP_LANG_ID:3342699,25&cs=1FC22FDE02FD51137ADC6BE8CA4E10E8F 

The missing two standards, EN 18239 and EN 18246 are in formal vote process until mid of July, and should be published in early autumn.

Therefore, current status of the freeDPP project covers protocols, storage, interoperability, API, serialisation and identification schemes as described in EN 18216, 18219, 18220, 18221, 18222 and 18223.

We intend first commit in early July 2026 after current testing and documentation process.

Info about ESPR:
----------------
The ESPR came into force in mid-July 2024 and is the cornerstone for more environmentally sustainable and circular products. It thus replaces the Ecodesign Directive 2009/125/EC, expands its scope and will in future regulate almost all physical products that are placed on the market or put into operation in the EU. The ESPR is intended to ensure that only durable, repairable and energy-efficient products are traded on the internal market in the future.
Foodstuffs, animal feed, medicinal products, veterinary medicinal products, live plants/animals/micro-organisms, products of human origin, products of plants and animals directly related to their future reproduction and certain vehicles are excluded.

functionalities:
-----
background database:
-----
RDBMS database template including test data to be provided here.
normalized table structure allows adaption into different RDBMS Systems.

dpp data maintenance:
-----
A web-based administration interface enables the import, recording and maintenance of product-specific DPP data in accordance with the sector-specific requirements of the applicable delegated act. Currently this GUI-part is provided for free access, but not as open source.

publication:
-----
Provision of the DPP in accordance with the requirements of European harmonised standards as a REST endpoint, including mapping functionality of the links on the data carriers (e.g. QR code on the product) to the API. Provision in both machine-readable and human-readable form.
 
repository - integration:
-----
The description of the sector-specific data points required is provided in so-called ‘dictionaries’, which are expected (but not yet confirmed as of December 2025) to be made available via a shared repository. This will allow the information in the respective DPP to be interpreted uniformly – in different languages!

software - integration:
-----
A class library is provided which enables the integration of DPP data access into any application.

technology stack:
-----
background database:
-----
system can be run on any kind of MS SQL-Server, including free SQL-Server Express.
further, even open source RDBMS may be adapted later

languages:
-----
back-end: .net core 8.0 / c#
delivery: JSON (as required by standards)
client side rendering to HTML 5.0 via javascript and CSS3

security:
-----
security frameworks according EN 18239 and EN 18246 to be delivered after publication of these standards


