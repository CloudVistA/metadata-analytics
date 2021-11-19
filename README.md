
# VISTA Metadata Analytics

__*The VISTA Metadata Analytics Program is a semantic web standards-driven approach to access, interfacing, security, and master data management for Veteran  health information at web-scale*__  

The VA Health Information Systems Technology and Architecture ([VISTA](https://en.wikipedia.org/wiki/VistA)) is the U.S. Department of Veterans Affairs integrated clinical, business, and administrative information system which supports the life-long care of 20 million veterans at over 1200 VA hospitals and clinics nationwide. The 130 VISTA systems in operation today contain over 400-million patient-years of data, and continue to grow at a rate of over four million new lab tests, radiographs, and documents each day. 

VISTA's data model - the roadmap to all of VA's institutional, business, and clinical processes and data - has evolved organically over the past thirty-five years across 130 VISTA systems, but has never been comprehensively exposed in computable form.  

In the VISTA Metadata Analytics Program, the VISTA Data Model is comprehensively exposed, enriched, and operationalized in a modern, secure, web-standard data model, allowing integration and semantic interoperability of all Veteran health data at web-scale.

![vdp](/images/linked-data-evolution.png)

# Master Linked Data Model
![](/images/vdp-introB.png)

## Metadata Processing - Overview
![](/images/vdp-basic.png)

## Metadata Processing - Detail
![](/images/vdp-technical.png)

## Master VISTA Data Model: Features

*__An operationalized Master VISTA Data Model (MVDM) provides VA with three key transformational capabilities:__*

VISTA<br>Data | Details
---|---
 ![db-search](https://github.com/vistadataproject/documents/blob/master/images/logos/logos-db/50h/db-search.jpg) <br> __Access__ | __A single, universal, industry-standard mechanism for reading and writing *all VISTA data*.__ <br> This mechanism is unified by the read model and the write write model integrated into a single, symmetric-read-write data model (VDM), with all data in industry-standard web formats. *This overcomes the well understood shortcoming with VISTA Data Read and Write, which uses completely unique code, models, and mechanisms for reading data as distinct from writing data. Furthermore, the 20+ year old RPCs - over 3300 MUMPS routines which encapsulate all these idiosyncratic approaches (written *exclusively* and in lock-step with the the Delphi code of CPRS, and none of which are documented or maintained) simply cannot be relied on going forward, particularly for generic, external non-CPRS interfaces and clients.*
![db-integrity](https://github.com/vistadataproject/documents/blob/master/images/logos/logos-db/50h/db-integrityA.jpg) <br> __Integrity__| __Comprehensive, automated, standardized, strict data integrity enforcement for  *all VISTA data*.__ <br> *This is a major improvement over the hodgepodge of legacy, ad-hoc methods that have accumulated over the past 35 years (HL7, RPCs, MUMPS, procedural code), none of which are documented, and all of which are inconsistent, unpredictable, and highly permissive*.  See also: [Master Data Management](https://en.wikipedia.org/wiki/Master_data_management)
![db-security](https://github.com/vistadataproject/documents/blob/master/images/logos/logos-db/50h/db-security.jpg) <br> __Security__ | __Comprehensive, industry-standard, fine-grained, data-centric security for *all VISTA data*.__ <br> Currently VISTA provides security for only a small fraction of its data, and does this through bespoke, complex, opaque, and unmaintainable methods hardwired to a legacy terminal interface and its 9000+ terminal menu options. <br> __Data-centric, attribute-based security__ is the foundation for all other security levels and technologies, because without knowledge of the data and its logical attributes, it will not be possible to provide the appropriate security measures on the data. <br>__Through metadata enrichment of the VISTA Data Model__, VISTA will know *what categories of data it is managing* and thus allow, for the first time, comprehensive, data-centric, attribute-based security "on-the-data" for all VISTA data, permitting the secure exchange of data. See [Data-Centric Security](https://en.wikipedia.org/wiki/Data-centric_security),  [Logical Security](http://www.mdpi.com/1999-5903/4/4/929/htm#fig_body_display_futureinternet-04-00929-f001), [Semantic Security](https://www.google.com/search?q=semantic+data+security&sa=X&biw=1154&bih=1062&tbm=isch&tbo=u&source=univ&ved=0ahUKEwi_14b--JXLAhWKOz4KHWghAVEQsAQIgwE) and [Attribute-Based Access Control (ABAC)](http://csrc.nist.gov/projects/abac)




## Master VISTA Data Model: Attributes

Attribute | Details
---|---
__Representative__  | __VDM operationalizes all relevant VA VISTA data to the maximum extent available.__ <br> The VISTA Data Model comprises the current existing data-driven architecture of VISTA, and thus leverages all existing VISTA definitions. There is 100% correspondence and coverage of the internal data definitions of any local VISTA and that of its corresponding  VISTA Data Model (VDM), since these are maintained always in-sync and up-to-date. Any and all enhancements to any VISTA system and its data definitions will automatically be reflected in the VISTA Data Model through automated, triggered updates whenever VISTA's data dictionary is updated. 
__Real-Time__ | __VDM is operationalized using Best-of-Breed real-time server-side runtime technology.__<br> The same runtime technology that drives the largest commericial real-time high-traffic websites such as Walmart, eBay, PayPal, Netflix, Uber, LinkedIn, and the New York Times with millions of concurrent users also drives MVDM. *This maximizes transactional processing performance directly on the transactional database.*
__Noninvasive__ | __VDM provides VISTA with essential new functionality within the current VISTA architecture 'as is', without modification.__ <br>  No existing VISTA code, routines, packages, modules, infrastructure, or functionality will be affected or changed in any way (i.e. this is a 'safe'and 'noninvasive'). This keeps all existing functionality, while offering new, essential functionality for parallel development of all new web-oriented clients. In addition, it makes it easy and 'safe' to install, as this does not affect any current code or functionality.
__Self-Contained__ | __VDM runs server-side, in-process, directly within the existing VISTA/M transaction engine.__ <br> This eliminates all moving parts and maximizes transaction processing performance by running as an embedded process directly within the local M transactional database, fully leveraging the 'as-is' VISTA architecture. *This makes it extremely performant - at native speed of the MUMPS transaction engine. It also makes it easy to deploy and maintain. No moving parts. No external dependencies. No middleware. "On the metal" native M server-side performance*
__Data-Centric__ | __VDM is a completely new, purely data-centric approach to managing VISTA's data__. It does not involve changing a single line of VISTA's existing M procedural code, nor is it 'wrapping' (i.e. secretly using) any legacy code, routines, or RPCs dressed up within a shiny new encapsulation method (i.e. RPC wrapper "APIs"), which only add yet more obfuscation layers on the data. A data-centric approach __*comprehensively exposes all the data, which exposes the fact that VISTA has a data model*__ - which up to this point has not been realized nor taken advantage of. *This is the opposite of a code-centric approach, which obfuscates the data and its data model*.
__Web-Standard__ |  __VDM technologies are 100% web standard__ and all used in production settings by the worlds' largest corporations and organizations.  For further information see [standards and technologies](https://github.com/vistadataproject/documents/tree/master/Background#standards).
__Empiric Evolution__ | __VDM employs a new approach to emprically evolving VISTA's capabilities through rapid, iterative, functional prototypes.__ This allows the focus to remain on exploration of new techniques and approaches, rather than on more superficial end-user requirements, which rarely if ever attempt to tackle the deep conceptual and technological issues of data management. This is *the opposite waterfall development*.  See [spiral model](https://en.wikipedia.org/wiki/Spiral_model)



