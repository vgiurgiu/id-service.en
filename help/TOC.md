---
cloud: experience-cloud
product: adobe
archtype: end-user
user-guide: null
---

# Table of Contents {#table-of-contents}

+ [Experience Cloud ID Service](mcvid-home.md)
+ [Overview](mcvid-overview/mcvid-overview.md)
   + [Cookies and the Experience Cloud ID Service](mcvid-overview/mcvid-cookies.md)
   + [How the Experience Cloud ID Service requests and sets IDs](mcvid-overview/mcvid-id-request.md)
   + [Understanding ID synchronization and match rates](mcvid-overview/mcvid-match-rates.md)
+ [Implementation guides](mcvid-implementation-guides/mcvid-implementation-guides.md)
   + [Implement with Launch](mcvid-implementation-guides/ecid-implement-with-launch.md)
   + [Implementation with Dynamic Tag Management](mcvid-implementation-guides/mcvid-standard.md)
   + [Implement the Experience Cloud ID Service for Analytics](mcvid-implementation-guides/mcvid-setup-analytics.md)
   + [Implement the Experience Cloud ID Service for Target](mcvid-implementation-guides/mcvid-setup-target.md)
   + [Implement the Experience Cloud ID Service for Analytics and Audience Manager](mcvid-implementation-guides/mcvid-setup-aam-analytics.md)
   + [Implement the Experience Cloud ID Service for Analytics, Audience Manager, and Target](mcvid-implementation-guides/mcvid-setup-aam-analytics-target.md)
   + [Using the Experience Cloud ID Service with A4T and a Server-side Implementation of Target](mcvid-implementation-guides/ecid-a4t-target.md)
   + [Direct Integration with the Experience Cloud ID Service](mcvid-implementation-guides/mcvid-direct-integration.md)
   + [Direct Integration Use Cases](mcvid-implementation-guides/mcvid-direct-integration-examples.md)
   + [Test and verify the Experience Cloud ID Service](mcvid-implementation-guides/mcvid-test-verify.md)
   + Opt-in Documentation
      + [Opt-in Service](mcvid-implementation-guides/overview/overview.md)
         + [Setting up Opt-in Service](mcvid-implementation-guides/overview/getting-started.md)
         + [Validating Opt-in Service](mcvid-implementation-guides/overview/testing-optin-and-iab-plugin.md)
         + [Configuring Opt-in with Launch](mcvid-implementation-guides/overview/launch.md)
         + [Configuring Opt-in with DTM](mcvid-implementation-guides/overview/optin-dtm.md)
         + [Opt-in Use Cases](mcvid-implementation-guides/overview/use-cases.md)
         + [Opt-in Reference](mcvid-implementation-guides/overview/api.md)
         + [(beta) Using Opt-in Services with IAB Framework](mcvid-implementation-guides/overview/iab.md)
+ [ID Service API](mcvid-library/mcvid-library.md)
   + [Configurations](mcvid-library/mcvid-function-vars/mcvid-function-vars.md)
      + [audienceManagerServer and audienceManagerServerSecure](mcvid-library/mcvid-function-vars/mcvid-subdomain-config.md)
      + [cookieDomain](mcvid-library/mcvid-function-vars/mcvid-cookiedomain.md)
      + [cookieLifetime](mcvid-library/mcvid-function-vars/mcvid-cookielifetime.md)
      + [disableIdSyncs](mcvid-library/mcvid-function-vars/mcvid-disableidsync.md)
      + [disableThirdPartyCalls](mcvid-library/mcvid-function-vars/mcvid-disablethirdpartycalls.md)
      + [disableThirdPartyCookies](mcvid-library/mcvid-function-vars/mcvid-disable-cookies.md)
      + [idSyncAttachIframeOnWindowLoad](mcvid-library/mcvid-function-vars/mcvid-idsyncattachiframeonwindowload.md)
      + [idSyncContainerID](mcvid-library/mcvid-function-vars/mcvid-idsyncontainerid.md)
      + [idSyncSSLUseAkamai](mcvid-library/mcvid-function-vars/mcvid-idsyncssluseakamai.md)
      + [isCoopSafe](mcvid-library/mcvid-function-vars/mcvid-coopsafe.md)
      + [loadTimeout](mcvid-library/mcvid-function-vars/mcvid-loadtimeout.md)
      + [overwriteCrossDomainMCIDAndAID](mcvid-library/mcvid-function-vars/mcvid-overwrite-visitor-id.md)
      + [resetBeforeVersion](mcvid-library/mcvid-function-vars/mcvid-resetbeforeversion.md)
      + [sdidParamExpiry](mcvid-library/mcvid-function-vars/mcvid-sdidparamexpiry.md)
      + [secureCookie](mcvid-library/mcvid-function-vars/mcvid-securecookie.md)
      + [useCORSOnly](mcvid-library/mcvid-function-vars/mcvid-use-cors-only.md)
      + [whitelistParentDomain and whitelistIframeDomains](mcvid-library/mcvid-function-vars/mcvid-whitelistdomain.md)
   + [Methods](mcvid-library/mcvid-get-set/mcvid-get-set.md)
      + [appendSupplementalDataIDTo](mcvid-library/mcvid-get-set/mcvid-appendsupplementaldataidto.md)
      + [appendVisitorIDsTo (Cross-Domain Tracking)](mcvid-library/mcvid-get-set/mcvid-appendvisitorid.md)
      + [callTimeOut Methods](mcvid-library/mcvid-get-set/mcvid-timeout-functions.md)
      + [ID Synchronization by URL or Data Source](mcvid-library/mcvid-get-set/mcvid-idsync.md)
      + [getInstance](mcvid-library/mcvid-get-set/mcvid-getinstance.md)
      + [getAnalyticsVisitorID](mcvid-library/mcvid-get-set/mcvid-getanalyticsvisitorid.md)
      + [getCustomerIDs](mcvid-library/mcvid-get-set/mcvid-getcustomerids.md)
      + [setCustomerIDs](mcvid-library/mcvid-get-set/mcvid-setcustomerids.md)
      + [getMarketingCloudVisitorID](mcvid-library/mcvid-get-set/mcvid-getmcvid.md)
      + [getLocationHint](mcvid-library/mcvid-get-set/mcvid-getlocationhint.md)
      + [getVisitorValues](mcvid-library/mcvid-get-set/mcvid-getvisitorvalues.md)
      + [isClientSideMarketingCloudVisitorID](mcvid-library/mcvid-get-set/mcvid-client-side-id.md)
      + [resetState](mcvid-library/mcvid-get-set/mcvid-resetstate.md)
+ [Reference](mcvid-reference/mcvid-reference.md)
   + [Analytics Reference](mcvid-reference/mcvid-analytics-reference/mcvid-analytics-reference.md)
      + [Setting Analytics and Experience Cloud IDs](mcvid-reference/mcvid-analytics-reference/mcvid-analytics-ids.md)
      + [Order of Operations for Analytics IDs](mcvid-reference/mcvid-analytics-reference/mcvid-analytics-order-of-operations.md)
      + [Experience Cloud ID Service Migration Decision Points](mcvid-reference/mcvid-analytics-reference/mcvid-migration-decisions.md)
      + [Experience Cloud ID Service Migration Scenarios](mcvid-reference/mcvid-analytics-reference/mcvid-migration-scenarios.md)
      + [Analytics and Experience Cloud ID Requests](mcvid-reference/mcvid-analytics-reference/mcvid-legacy-analytics.md)
      + [Data Collection CNAMEs and Cross-Domain Tracking](mcvid-reference/mcvid-analytics-reference/mcvid-cname.md)
      + [Server-side Implementation Mixed with JavaScript](mcvid-reference/mcvid-analytics-reference/mcvid-server-side.md)
      + [The ID Service Grace Period](mcvid-reference/mcvid-analytics-reference/mcvid-grace-period.md)
   + [Content Security Policies and the Experience Cloud ID Service](mcvid-reference/mcvid-csp.md)
   + [COPPA Support in the Experience Cloud ID Service](mcvid-reference/mcvid-coppa.md)
   + [CORS Support in the Experience Cloud ID Service](mcvid-reference/mcvid-cors.md)
   + [Customer IDs and Authentication States](mcvid-reference/mcvid-authenticated-state.md)
   + [Get Region and User IDs From the AMCV Cookie or the ID Service](mcvid-reference/mcvid-regions.md)
   + [Requirements for the Experience Cloud ID Service](mcvid-reference/mcvid-requirements.md)
   + [Video Heartbeat and the Experience Cloud ID Service](mcvid-reference/mcvid-heartbeat.md)
   + [Data Workbench and the Experience Cloud ID Service](mcvid-reference/mcvid-dwb.md)
+ [FAQs](mcvid-faq-intro/mcvid-faq-intro.md)
   + [ID Service FAQs](mcvid-faq-intro/mcvid-faq.md)
   + [Analytics and ID Service FAQs](mcvid-faq-intro/mcvid-analytics-faq.md)
   + [FAQs for Other Experience Cloud Solutions](mcvid-faq-intro/mcvid-other-faq.md)
+ [2019 Release Notes](mcvid-release-notes/mcvid-release-notes.md)
   + [2018 Release Notes](mcvid-release-notes/mcvid-notes-2018.md)
   + [2017 Release Notes](mcvid-release-notes/mcvid-notes-2017.md)
   + [2016 Release Notes](mcvid-release-notes/mcvid-notes-2016.md)
   + [2015 Release Notes](mcvid-release-notes/mcvid-notes-2015.md)
+ [Contact, Privacy, and Legal](contact-and-legal.md)