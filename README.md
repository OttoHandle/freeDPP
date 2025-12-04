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

Info about ESPR:
----------------
The ESPR came into force in mid-July 2024 and is the cornerstone for more environmentally sustainable and circular products. It thus replaces the Ecodesign Directive 2009/125/EC, expands its scope and will in future regulate almost all physical products that are placed on the market or put into operation in the EU. The ESPR is intended to ensure that only durable, repairable and energy-efficient products are traded on the internal market in the future.
Foodstuffs, animal feed, medicinal products, veterinary medicinal products, live plants/animals/micro-organisms, products of human origin, products of plants and animals directly related to their future reproduction and certain vehicles are excluded.

functionalities:
-----
dpp data maintenance:
-----
A web-based administration interface enables the import, recording and maintenance of product-specific DPP data in accordance with the sector-specific requirements of the applicable delegated act.

publication:
-----
Provision of the DPP in accordance with the requirements of European harmonised standards as a REST endpoint, including mapping functionality of the links on the data carriers (e.g. QR code on the product) to the API. Provision in both machine-readable and human-readable form.
 
repository - integration:
-----
The description of the sector-specific data points required is provided in so-called ‘dictionaries’, which are expected (but not yet confirmed as of December 2025) to be made available via a shared repository. This will allow the information in the respective DPP to be interpreted uniformly – in different languages!

software - integration:
-----
A class library is provided which enables the integration of DPP data access into any application.
