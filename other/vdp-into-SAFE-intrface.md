
# VISTA Data Project

The Veterans Information Systems Technology Architecture (VISTA) is the U.S. Department of Veterans Affairs comprehensive integrated  clinical, business, and administrative information system that supports the operations of over 1200 VA hospitals and clinics nationwide.  

The VISTA Data Project is a new data-centric, model-driven approach to VISTA master data management, interfacing, and security.  VISTA's data model - the roadmap to all of VA's institutional, business, and clinical processes and data - has evolved organically over the past 35 years, but has not been surfaced and leveraged in computable form. 

Now, for the first time, VISTA's native data model - the __VISTA Data Model__ (VDM) - will be comprehensively exposed, enriched, and operationalized as a single, secure, symmetric read-write, server-side interface to all clinical operational VISTA data.  

The VISTA Data Model is in turn normalized across all local VISTA models creating a national, standardized __Master VISTA Data Model__ (MVDM), alowing transactions across all 100+ VISTA systems enterprise-wide using a single, standard, secure mechanism. This new secure enterprise interface is called the Secure Access Framework for the Enterprise (SAFE).


### VISTA's new SAFE Interface

Current VISTA interfaces, both new and old, wrap legacy code and remote procedure calls (RPCs) within various __mid-tier__  models __above the RPCs__ (figure below, left). This dependency on and encapsulation of RPCs within a mid-tier model not only fails to remediate, but propagates forward all the problems inherent with the legacy MUMPS code and RPCs - most notably lack of auditing and security.

In contrast, the Master VISTA Data Model (MVDM) is a __server-side__ model  __below the RPCs__ (figure below, right), and thus allows new, parallel interface paths. For legacy clients, this supports a backwards-compatible interface that audits, isolates, and secures legacy RPCs above the MVDM within the __RPC Locker__. For  new clients, __MVDM Services__ provide modern secure interfacing services directly to MVDM, eliminating the need for any legacy code or infrastructure, and allows rapid new client creation with the most current tools and technologies. 

This transition of VISTA's interface from insecure legacy RPC code wrappers to a master data model-driven __Secure Access Framework for the Enterprise (SAFE)__ is summarized in the figure below.


![VISTA-SAFE](https://github.com/vistadataproject/documents/blob/master/images/VISTA-SAFE-20170304.png)
<br><br><br>

For a technical overview of the VISTA Data Project, [click here](https://github.com/vistadataproject/documents/tree/master/Background)


