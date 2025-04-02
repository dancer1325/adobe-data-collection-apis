---
title: Data collection API endpoints
description: Learn what endpoints are available and how you can use them.
---
# Data collection API endpoints

* Adobe Experience Platform Edge Network
  * provides
    * optimized way -- to send data to -- ANY 
      * Adobe Experience Cloud product or 
      * Adobe Experience Platform service
  * [Video](https://video.tv.adobe.com/v/341448/)
    * TODO:

* Endpoints
  * / category
    * **Edge Network API**
      * [`interact`](interact/index.md)
      * [`collect`](collect/index.md)
      * supports
        * client-to-server API calls
        * server-to-server API calls
    * **Media Edge API**
      * == 18 endpoints
      * ⚠️ONLY supports client-to-server⚠️
      * Authenticated API calls -> use `server.adobedc.net` endpoints
      * Non-authenticated API calls -> use `edge.adobedc.net` endpoints
  * allows
    * Reduced page load time
    * Improved latency
    * First-party data collection
    * Streamlined, server-side communication between services
  * ⚠️ subject to additive changes & change behavior WITHOUT notice ⚠️

## Authenticated data collection

* Authenticated API calls
  * allow for
    * 👀secure collection of sensitive data 👀 
