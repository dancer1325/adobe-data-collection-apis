---
title: Adobe Experience Platform Data Collection APIs
description: Overview of the Adobe Experience Platform data collection APIs.
---

# Adobe Experience Platform data collection APIs

* allows, ACROSS your organization,
  * ingest,
  * standardize,
  * persist customer data

## Resources

* [Quick start guide](getting-started/index.md)
* [Endpoint guides](endpoints/index.md)
* [API reference](api/index.md)
* [Github repository](https://github.com/AdobeDocs/data-collection-apis)

## Overview

* Data collection libraries,
  * ' methods
    * make easier use of these endpoints
* ways to call data collection endpoints
  * DIRECTLY
  * -- via --
    * Web SDK or
    * Mobile SDK

## Categories of endpoints

* **Edge Network API**
  * == MOST straightforward way -- to send -- data | Adobe 
    * ways to invoke the methods
      * authenticated
      * non-authenticated
* **Media Edge API**
  * == endpoints / 
    * allow you 
      * -- to send -- media tracking data | Adobe
      * -- to compose -- streaming media session | Adobe's servers
        * | complete the session completes, those events are
          * -- aggregated into a -- smaller number of events
          * -- sent to the -- desired datastream
    * requirements
      * Streaming Media Collection Add-on

## Additional Information

* [Adobe Experience Platform API documentation](https://developer.adobe.com/experience-platform-apis/)
