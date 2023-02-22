# like.github.io

<!DOCTYPE html>
<!-- saved from url=(0078)https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><style type="text/css">.truste_caIcon_display {display: block !important;}</style><style type="text/css">.truste_cursor_pointer {cursor: pointer;}.truste_border_none {border: none;}</style>
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        
        <meta name="viewport" content="width=device-width, initial-scale=1">
        
        
        <link rel="stylesheet" href="./Oracle Access Management 12.2.1.4.0 - new_files/site.css">
        <script type="text/javascript" async="" src="./Oracle Access Management 12.2.1.4.0 - new_files/infinity_common.js.download"></script><script data-main="/sp_common/site-template/ohc-site-template/js/site-config" src="./Oracle Access Management 12.2.1.4.0 - new_files/require.js.download"></script>
        <script>
        if(window.require === undefined) {
          document.write('<script data-main="sp_common/site-template/ohc-site-template/js/site-config" src="sp_common/site-template/requirejs/require.js"><\/script>');
          document.write('<link href="sp_common/site-template/ohc-site-template/css/site.css" rel="stylesheet">');
        }
        </script>
        <link rel="shortcut icon" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/favicon.ico">
        
                <title>Oracle Access Management 12.2.1.4.0 - Install</title>
                <meta name="description" content="Documentation for system administrators that describes how to install and configure Oracle Access Management.">
                <meta property="og:description" content="Documentation for system administrators that describes how to install and configure Oracle Access Management.">
                <meta property="og:site_name" content="Oracle Help Center">
                <meta name="generator" content="Oracle Interface Page Generator 1.7.07.20">
                <meta property="og:title" content="Oracle Access Management 12.2.1.4.0 - Install">
                
                
                <link rel="schema.dcterms" href="http://purl.org/dc/terms/">
                <meta name="dcterms.created" content="2021-10-19T09:27:52.486Z">
                
                <meta name="dcterms.dateCopyrighted" content="2021">
                <meta name="dcterms.category" content="middleware">
                <meta name="dcterms.product" content="en/middleware/idm/access-manager/12.2.1.4">
                
        

    
    <meta name="dcterms.title" content="Oracle Access Management 12.2.1.4.0">
    <meta name="dcterms.identifier" content="en/middleware/idm/access-manager/12.2.1.4">
    <meta name="dcterms.release" content="Release 12.2.1.4">
  <script id="ssot-metadata" type="application/json"> {"primary":{"category":{"short_name":"middleware","element_name":"Middleware","display_in_url":true},"suite":{"short_name":"idm","element_name":"Identity Management (IdM)","display_in_url":true},"product_group":{"short_name":"not-applicable","element_name":"Not Applicable","display_in_url":false},"product":{"short_name":"access-manager","element_name":"Access Manager","display_in_url":true},"release":{"short_name":"12.2.1.4","element_name":"Release 12.2.1.4","display_in_url":true}}} </script>
    <script type="application/ld+json"> {"@context":"https://schema.org","@type":"WebPage","name":"Oracle Access Management 12.2.1.4.0 - Install","description":"Documentation for system administrators that describes how to install and configure Oracle Access Management.","datePublished":"2019-09-27 04:52:15 PDT","dateModified":"2021-10-19 02:29:39 PDT"} </script>
    <script>window.ohcglobal || document.write('<script src="/en/dcommon/js/global.js">\x3C/script>')</script><script src="./Oracle Access Management 12.2.1.4.0 - new_files/global.js.download"></script><script type="text/javascript" charset="utf-8" async="" data-requirecontext="_" data-requiremodule="site-config" src="./Oracle Access Management 12.2.1.4.0 - new_files/site-config.js.download"></script><script src="./Oracle Access Management 12.2.1.4.0 - new_files/oracle-universal.js.download"></script><link rel="shortcut icon" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon.ico"><link rel="icon" sizes="16x16 32x32 64x64 120x120" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon.ico"><link rel="icon" type="image/png" sizes="270x270" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-270.png"><link rel="icon" type="image/png" sizes="196x196" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-192.png"><link rel="icon" type="image/png" sizes="96x96" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-128.png"><link rel="icon" type="image/png" sizes="32x32" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-32.png"><link rel="apple-touch-icon" sizes="120x120" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-120.png"><link rel="apple-touch-icon" sizes="152x152" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-152.png"><link rel="apple-touch-icon" sizes="180x180" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-180.png"><link rel="apple-touch-icon" sizes="270x270" href="https://docs.oracle.com/sp_common/site-template/ohc-common/img/o-icon/favicon-270.png"><meta name="msapplication-TileColor" content="#FFFFFF"><meta name="msapplication-TileImage" content="/sp_common/site-template/ohc-common/img/o-icon/favicon-152.png"><meta name="msapplication-config" content="/sp_common/site-template/ohc-common/img/o-icon/browserconfig.xml"><script type="text/javascript" src="./Oracle Access Management 12.2.1.4.0 - new_files/odc.js.download"></script><script type="text/javascript" src="./Oracle Access Management 12.2.1.4.0 - new_files/analytics-production.js.download" async="true" defer="true"></script><script type="text/javascript" src="./Oracle Access Management 12.2.1.4.0 - new_files/common.js.download" async="true" defer="true"></script><script type="text/javascript" src="./Oracle Access Management 12.2.1.4.0 - new_files/analytics.js.download" async="true" defer="true"></script></head>
    <body>
        <noscript>
            <div>JavaScript must be enabled to correctly display this content</div>
        </noscript>
    
                <div class="ohc-grid">
                    <div role="banner"><!-- U02v0 -->
  <div class="u02z86d"></div><nav role="navigation" class="u02nav ocom-base ocom-responsive" aria-label="Main">
    <div class="u02 u02dtop u02init" id="u02">
      <div id="u02skip2content">
        <ul>
          <li><a id="u02skip2c" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#maincontent" tabindex="0">Skip to Content</a></li>
          <li><a id="skip-search" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#skip_to_search_form" tabindex="0">Skip to Search</a></li>
          <li><a aria-label="Navigate to help center home page" href="https://docs.oracle.com/" tabindex="0">Home</a></li>
        </ul>
      </div>
      <div class="u02w1">

        <!-- logo -->
        <div class="u02logos" data-trackas="header">
          <div class="u02logow1">
            <a aria-label="Navigate to Oracle.com home page" data-trackas="header" class="o_icon new-window" href="https://www.oracle.com/" data-lbl="logo" target="_blank">
            </a>
          </div>
        </div>

        <!-- menu -->
        <a id="mobisearch" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#search"><span><i class="u02i1"></i><i class="u02i2"></i></span></a><div class="u02menu" data-trackas="menu" role="application">
          <div id="u02main" class="u02mlink u02haml">
            <div class="u02mlinkw1">
              <a aria-label="Main Menu (links open on the same page), use arrow keys to move through elements" id="u02menulink" data-lbl="menu" aria-haspopup="true" aria-controls="menubar1"><div class="u02hamenu"><span class="m1"></span><span class="m2"></span><span class="m3"></span><span class="m4"></span></div>
              </a>
            </div>
          <div class="u02menu-l1z1"><i></i></div><div id="u02mainmenu" class="u02menucontent u02mainmenu">
        <!-- LVL 1 -->
        <div class="u02menu-l1 u02menuwrap u02mheight u02menu-nomn" style="height: 557px;">
          <ul aria-labelledby="u02menulink" id="menubar1" role="menu" class="u02menu-ul">
            <!-- ############## CLOUD APPLICATIONS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Cloud Applications">
                Cloud Applications
              </a>
              <!-- LVL 2 -->
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="cloud-applications" style="height: 557px;">
                <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">
                Cloud Applications
              </a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Fusion Applications Suite" data-lbl="fusion-applications-suite" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/saas&amp;id=fa-home" class="u02xlink">Fusion Applications Suite</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="NetSuite Applications" data-lbl="netSuite-applications" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/saas/netsuite&amp;id=netsuite" class="u02xlink">NetSuite Applications</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Industry-Specific Applications" data-lbl="industry-specific-applications" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/industries&amp;id=industries-docs" class="u02xlink">Industry-Specific Applications</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Advertising (Data Cloud)" data-lbl="advertising" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/saas/data-cloud&amp;id=daasmarketinggs" class="u02xlink">Advertising (Data Cloud)</a></li>
                 </ul>
              </div>
              <!-- / LVL 2 -->
            </li>
            <!-- ############## CLOUD INFRASTRUCTURE ##############-->
           <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Cloud infrastructure">
                Cloud Infrastructure
              </a>
                <!-- LVL 2 -->
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="cloud-infrastructure" style="height: 557px;">
                <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">
                Cloud Infrastructure
              </a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Get started" data-lbl="get-started" href="https://docs.oracle.com/en-us/iaas/Content/GSG/Concepts/baremetalintro.htm" class="u02xlink">Get Started</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Free tier" data-lbl="free-tier" href="https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier.htm" class="u02xlink">Free Tier</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Government cloud" data-lbl="government-cloud" href="https://docs.oracle.com/en-us/iaas/Content/General/Concepts/govlanding.htm" class="u02xlink">Government Cloud</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Services" data-lbl="services" href="https://docs.oracle.com/en-us/iaas/Content/services.htm" class="u02xlink">Services</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Developer resources" data-lbl="developer-resources" href="https://docs.oracle.com/en-us/iaas/Content/devtoolshome.htm" class="u02xlink">Developer Resources</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Security" data-lbl="security" href="https://docs.oracle.com/en-us/iaas/Content/Security/Concepts/security.htm" class="u02xlink">Security</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="More resources" data-lbl="more-resources" href="https://docs.oracle.com/en-us/iaas/Content/General/Reference/more.htm" class="u02xlink">More Resources</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Launch infrastructure console" data-lbl="launch-infrastructure-console" href="https://console.us-phoenix-1.oraclecloud.com/" class="u02xlink">Launch Infrastructure Console</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Cloud infrastructure" data-lbl="all-cloud-infrastructure" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/iaas&amp;id=oci-home" class="u02xlink">All Cloud Infrastructure</a></li>
                 </ul>
              </div>
                <!-- / LVL 2 -->
            </li>
            <!-- ############## ON-PREMISES APPLICATIONS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
                <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="On-premises applications">
                  On-Premises Applications
                </a>
                <!-- LVL 2 -->
                <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="applications" style="height: 557px;">
                  <ul role="menui" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">
                  On-Premises Applications
                </a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="fusion applications on premises" data-lbl="fusion-apps-premise" href="https://docs.oracle.com/en/applications/fusion-apps/index.html" class="u02xlink">Fusion Applications On Premises</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="enterprise performance management" data-lbl="enterprise-performance-management" href="https://docs.oracle.com/en/applications/enterprise-performance-management/index.html" class="u02xlink">Enterprise Performance Management</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="e-business" data-lbl="e-business" href="https://docs.oracle.com/en/applications/e-business-suite/index.html" class="u02xlink">E-Business</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="peopleSoft" data-lbl="peoplesoft" href="https://docs.oracle.com/en/applications/peoplesoft/index.html" class="u02xlink">PeopleSoft</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="siebel" data-lbl="siebel" href="https://docs.oracle.com/en/applications/siebel/index.html" class="u02xlink">Siebel</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="JD edwards" data-lbl="jd-edwards" href="https://docs.oracle.com/en/applications/jd-edwards/index.html" class="u02xlink">JD Edwards</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="oracle applications" data-lbl="all-applications" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/applications&amp;id=onprem-apps-docs" class="u02xlink">All Applications</a></li>
                  </ul>
                </div>
                <!-- / LVL 2 -->
            </li>
            <!-- ############## MIDDLEWARE ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
                <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Middleware">
                    Middleware
                  </a>
                <!-- LVL 2 -->
                <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="middleware" style="height: 557px;">
                    <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">
                    Middleware
                  </a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="business intelligence" data-lbl="business-intelligence" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menubi" class="u02xlink">Business Intelligence</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="data integrator" data-lbl="data-integrator" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menudi" class="u02xlink">Data Integrator</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="enterprise manager" data-lbl="enterprise-manager" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuem" class="u02xlink">Enterprise Manager</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="goldengate" data-lbl="golden-gate" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menugg" class="u02xlink">GoldenGate</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="identity management" data-lbl="identity-management" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuidm" class="u02xlink">Identity Management</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="JavaScript extension toolkit" data-lbl="javascript-extension-toolkit" href="https://docs.oracle.com/pls/topic/lookup?ctx=jetlatest&amp;id=homepage" class="u02xlink">JavaScript Extension Toolkit</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="platform security services" data-lbl="platform-security-services" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuopss" class="u02xlink">Platform Security Services</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="SOA suite" data-lbl="soa-suite" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menusoa" class="u02xlink">SOA Suite</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="webcenter" data-lbl="webcenter" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuwc" class="u02xlink">WebCenter</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="weblogic server" data-lbl="weblogic-server" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuwls" class="u02xlink">WebLogic Server</a></li>
                      <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="middleware documentation" data-lbl="all-middleware" href="https://docs.oracle.com/pls/topic/lookup?ctx=fmwlatest&amp;id=menuall" class="u02xlink">All Middleware</a></li>
                    </ul>
                  </div>
                  <!-- / LVL 2 -->
            </li>
            <!-- ############## DATABASE ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Database">Database</a>
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="database" style="height: 557px;">
                <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Database</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="big data" data-lbl="big-data" href="https://docs.oracle.com/en/bigdata/index.html" class="u02xlink">Big Data</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="enterprise manager" data-lbl="enterprise-manager" href="https://docs.oracle.com/en/enterprise-manager/index.html" class="u02xlink">Enterprise Manager</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="oracle database" data-lbl="oracle-database" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/database&amp;id=oracle-database-getstarted" class="u02xlink">Oracle Database</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="other databases" data-lbl="other-databases" href="https://docs.oracle.com/en/database/other-databases/index.html" class="u02xlink">Other Databases</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="database documentation" data-lbl="all-database" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/database&amp;id=database-docs" class="u02xlink">All Database</a></li>
                </ul>
              </div>
            </li>
            <!-- ############## ENGINEERED SYSTEMS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Engineered systems">Engineered Systems</a>
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="engineered-systems" style="height: 557px;">
                  <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Engineered Systems</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="advanced support gateway" data-lbl="advanced-support-gateway" href="https://docs.oracle.com/cd/E41177_01/index.html" class="u02xlink">Advanced Support Gateway</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="autonomous health checks and diagnostics" data-lbl="autonomous-health-checks-and-diagnostics" href="https://docs.oracle.com/en/engineered-systems/health-diagnostics/" class="u02xlink">Autonomous Health Checks and Diagnostics</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="big data appliance" data-lbl="big-data-appliance" href="https://docs.oracle.com/en/bigdata/big-data-appliance/" class="u02xlink">Big Data Appliance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="database appliance" data-lbl="database-appliance" href="https://docs.oracle.com/en/engineered-systems/oracle-database-appliance/" class="u02xlink">Database Appliance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="enterprise manager" data-lbl="enterprise-manager" href="https://docs.oracle.com/en/enterprise-manager/index.html" class="u02xlink">Enterprise Manager</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="exadata database machine" data-lbl="exadata-database-machine" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/engineered-systems/exadata-database-machine&amp;id=homepage" class="u02xlink">Exadata Database Machine</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="exalogic elastic cloud" data-lbl="exalogic-elastic-cloud" href="https://docs.oracle.com/cd/E18476_01/index.htm" class="u02xlink">Exalogic Elastic Cloud</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="exalytics in-memory machine" data-lbl="exalytics-in-memory-machine" href="https://docs.oracle.com/en/engineered-systems/index.html#OracleExalyticsIn-MemoryMachine" class="u02xlink">Exalytics In-Memory Machine</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="minicluster" data-lbl="minicluster" href="https://docs.oracle.com/cd/E69469_01/index.html" class="u02xlink">MiniCluster</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="private cloud appliance" data-lbl="private-cloud-appliance" href="https://docs.oracle.com/en/engineered-systems/private-cloud-appliance/" class="u02xlink">Private Cloud Appliance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="supercluster" data-lbl="supercluster" href="https://docs.oracle.com/en/engineered-systems/index.html#OracleSuperCluster" class="u02xlink">SuperCluster</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="zero data loss recovery appliance" data-lbl="zero-data-loss-recovery-appliance" href="https://docs.oracle.com/en/engineered-systems/zero-data-loss-recovery-appliance/" class="u02xlink">Zero Data Loss Recovery Appliance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="ZFS storage appliance" data-lbl="zfs-storage-appliance" href="https://www.oracle.com/technetwork/documentation/oracle-unified-ss-193371.html#nas" class="u02xlink">ZFS Storage Appliance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="engineered systems documentation" data-lbl="supercluster" href="https://docs.oracle.com/en/engineered-systems/index.html" class="u02xlink">All Engineered Systems</a></li>
                  </ul>
                </div>
            </li>
            <!-- ############## JAVA ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Java">Java</a>
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="java" style="height: 557px;">
                <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Java</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="java EE" data-lbl="java-ee" href="https://docs.oracle.com/javaee/7/index.html" class="u02xlink">Java EE</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="java embedded" data-lbl="java-embedded" href="https://docs.oracle.com/javame/8.3/index.html" class="u02xlink">Java Embedded</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="java SE" data-lbl="java-se" href="https://www.oracle.com/pls/topic/lookup?ctx=en/java/javase&amp;id=javaselatest" class="u02xlink">Java SE</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="java documentation" data-lbl="all-java" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/java&amp;id=java-docs" class="u02xlink">All Java</a></li>
                </ul>
              </div>
            </li>
            <!-- ############## SYSTEMS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
                <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Systems">Systems</a>
                <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="systems" style="height: 557px;">
                  <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Systems</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="networking" data-lbl="networking" href="https://docs.oracle.com/en/networking/index.html" class="u02xlink">Networking</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="servers" data-lbl="servers" href="https://docs.oracle.com/en/servers/index.html" class="u02xlink">Servers</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="storage" data-lbl="storage" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/storage&amp;id=storage-docs" class="u02xlink">Storage</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="systems documentation" data-lbl="all-systems" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/systems&amp;id=systems" class="u02xlink">All Systems</a></li>
                  </ul>
                </div>
            </li>
             <!-- ############## OPERATING ENVIRONMENTS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
                <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Operating Environments">Operating Environments</a>
                <!-- LVL 2 -->
                <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="operating-environments" style="height: 557px;">
                  <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Operating Environments</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Operating Systems" data-lbl="operating-systems" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/operating-systems&amp;id=os-docs" class="u02xlink">Operating Systems</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Virtualization" data-lbl="virtualization" href="https://docs.oracle.com/en/virtualization/" class="u02xlink">Virtualization</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="operating environments documentation" data-lbl="all-operating-environments" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/operating-environments&amp;id=operating-environments" class="u02xlink">All Operating Environments</a></li>
                  </ul>
                </div>
            </li>
            <!-- ############## VIRTUALIZATION ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Virtualization">Virtualization</a>
              <!-- LVL 2 -->
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="virtualization" style="height: 557px;">
                  <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Virtualization</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="oracle linux virtualization manager" data-lbl="linux-virtualization-manager" href="https://docs.oracle.com/cd/F15085_01/index.html" class="u02xlink">Oracle Linux Virtualization Manager</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="oracle VM" data-lbl="vm" href="https://docs.oracle.com/en/virtualization/index.html#OracleVM" class="u02xlink">Oracle VM</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="oracle VM virtualbox" data-lbl="vm-virtualBox" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/virtualization&amp;id=virtualbox-getstarted" class="u02xlink">Oracle VM VirtualBox</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="secure global desktop" data-lbl="secure-global-desktop" href="https://www.oracle.com/technetwork/documentation/sgd-193668.html" class="u02xlink">Secure Global Desktop</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="virtualization documentation" data-lbl="all-virtualization" href="https://docs.oracle.com/en/virtualization/index.html" class="u02xlink">All Virtualization</a></li>
                  </ul>
              </div>
            </li>
            <!-- ############## INDUSTRY-SPECIFIC APPLICATIONS ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Industry-Specific Applications">Industry-Specific Applications</a>
                <!-- LVL 2 -->
                <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="industry-specific-applications" style="height: 557px;">
                  <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Industry-Specific Applications</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="communications" data-lbl="communications" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/industries&amp;id=industries-comm-getstarted" class="u02xlink">Communications</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="construction and engineering" data-lbl="construction-and-engineering" href="https://docs.oracle.com/en/industries/construction-engineering/index.html" class="u02xlink">Construction and Engineering</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Energy and Water" data-lbl="energy-and-water" href="https://docs.oracle.com/en/industries/utilities/index.html" class="u02xlink">Energy and Water</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="financial services" data-lbl="financial-services" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/industries&amp;id=industries-financial-services-getstarted" class="u02xlink">Financial Services</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="food and beverage" data-lbl="food-and-beverage" href="https://docs.oracle.com/en/industries/food-beverage/index.html" class="u02xlink">Food and Beverage</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="health" data-lbl="health" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/industries&amp;id=industries-health-getstarted" class="u02xlink">Health</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="health sciences" data-lbl="health-sciences" href="https://docs.oracle.com/en/industries/health-sciences/index.html" class="u02xlink">Health Sciences</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="hospitality" data-lbl="hospitality" href="https://docs.oracle.com/en/industries/hospitality/index.html" class="u02xlink">Hospitality</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="insurance" data-lbl="insurance" href="https://docs.oracle.com/en/industries/insurance/index.html" class="u02xlink">Insurance</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="public sector" data-lbl="public-sector" href="https://www.oracle.com/technetwork/documentation/pubsectrevmgmt-154608.html" class="u02xlink">Public Sector</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="retail" data-lbl="retail" href="https://docs.oracle.com/en/industries/retail/index.html" class="u02xlink">Retail</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="state and local" data-lbl="state-local" href="https://docs.oracle.com/en/industries/state-and-local/index.html" class="u02xlink">State and Local</a></li>
                    <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="industries documentation" data-lbl="all-industries" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/industries&amp;id=industries-docs" class="u02xlink">All Industries</a></li>
                 </ul>
                </div>
            </li>
            <!-- ############## ARCHITECTURE CENTER ##############-->
            <li role="none" class="u02menu-hasm u02menu-li">
              <a class="u02tlink" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#open" role="menuitem" aria-haspopup="true" aria-label="Architecture Center">Architecture Center</a>
                <!-- LVL 2 -->
              <div role="none" class="u02menu-l2 u02menuwrap u02mheight" data-lbl="cloud-infrastructure" style="height: 557px;">
                <ul role="menu" class="u02menu-ul"><li class="u02menuback u02nosub u02menu-li"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#back" class="u02blink">Architecture Center</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Reference Architectures" href="https://docs.oracle.com/solutions/?q=&amp;cType=reference-architectures&amp;sort=date-desc&amp;lang=en" class="u02xlink">Reference Architectures</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Solution Playbooks" href="https://docs.oracle.com/solutions/?q=&amp;cType=solution-playbook&amp;sort=date-desc&amp;lang=en" class="u02xlink">Solution Playbooks</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="Built &amp; Deployed" href="https://docs.oracle.com/solutions/?q=&amp;cType=built-deployed&amp;sort=date-desc&amp;lang=en" class="u02xlink">Built &amp; Deployed</a></li>
                  <li role="none" class="u02nosub u02menu-li"><a role="menuitem" aria-label="All Architecture Center" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/solutions&amp;id=solutions-home" class="u02xlink">All Architecture Center</a></li>
                </ul>
              </div>
            </li>
            <!-- ############## TUTORIALS AND LABS ##############-->
            <li role="none" class="u02nosub u02menu-li">
              <a role="menuitem" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/learn&amp;id=learn-home" class="u02xlink">Tutorials and Labs</a>
              <!-- / LVL 2 -->
              <hr role="none">
            </li>
            <!-- ############## ALL SERVICES & PRODUCTS ##############-->
            <li role="none" class="u02nosub u02menu-li">
              <a role="menuitem" aria-label="all services and products" href="https://docs.oracle.com/pls/topic/lookup?ctx=en&amp;id=a-z" class="u02xlink">All Services &amp; Products</a>
            </li>
            <!-- ############## HELP CENTER ##############-->
            <li role="none" class="u02nosub u02menu-li">
              <a role="menuitem" aria-label="help center home" href="https://docs.oracle.com/" class="u02xlink">Help Center Home</a>
            </li>
            <!-- ############## ORACLE.COM ##############-->
            <li role="none" class="u02nosub u02menu-li">
              <a role="menuitem" aria-label="oracle.com home" href="https://www.oracle.com/index.html" class="u02xlink">Oracle.com Home</a>
              <hr role="none">
            </li>
            <li role="none" class="u02nosub u02menu-li">
              <a role="menuitem" aria-label="Get started with cloud" href="https://docs.oracle.com/en/cloud/index.html" class="u02xlink">Get started with Cloud</a>
            </li>
          </ul>
        </div>
        <!-- / LVL 1 -->
      </div></div>
        </div>

        <!-- local label -->
        <div class="u02local" data-trackas="header">
          <div class="u02localw1">
              <a aria-label="Navigate to help center home page" id="u02localink" href="https://docs.oracle.com/" data-trackas="header" data-lbl="local">
                <span>Help Center</span>
              </a>
          </div>
        </div>

        <!-- search -->
        <div id="u02search" class="u02search" data-trackas="header" style="display: none">
          <form class="u02searchform" name="searchForm" method="get" action="https://docs.oracle.com/apps/search/search.jsp?">
            <input type="text" id="txtSearch" class="textcnt autoclear" name="q" placeholder="Search" aria-label="Search input text area" autocomplete="off" aria-owns="awesomplete_list_1">
            <input aria-label="submit search" class="u02searchbttn" type="submit" aria-hidden="true">
          </form>
        </div>

        <!-- UTILITY BAR -->
        <!--Search Bar-->
        <div id="search-bar-container" class="background-white">
          <div id="search-icon">
            <span id="search-icon-black" role="presentation"></span>
            <span id="search-icon-white" role="presentation" class="preview-hide"></span>
          </div>
          <div id="search-bar-scope">
    <div id="search-bar-scope-book" class="scope-product-icon" role="none" aria-hidden="true"></div>
    <div id="white-pipe" style="display: none; height: 16px; width: 1px; background-color: #fcfbfa; opacity: 0.15; padding-right: 1px;"></div>
    <span id="search-bar-scope-text">Access Manager Release 12.2.1.4</span>
    <button id="search-bar-scope-close" aria-label="Search is scoped by Access Manager Release 12.2.1.4. Press enter to remove scope"><span id="search-bar-scope-close-icon"></span></button>

    <div id="search-scope-tooltip" class="tooltip tooltip-hide" style="opacity: 1;" role="tooltip">
      <div class="tooltip-inner">
        <div id="search-bar-scope-tooltip" aria-hidden="true">
          <p class="grayed-font">Search is scoped to:</p>
          <p class="black-font">Access Manager Release 12.2.1.4</p>
        </div>
      </div>
    </div>
  </div>
          <form class="u02searchform" name="searchForm" method="GET" action="https://docs.oracle.com/search/?">
            <input id="search-bar-input" name="q" placeholder="Search" aria-label="Search input text area" autocomplete="off" class="background-white black-placeholder">
          <input type="hidden" name="category" value="middleware"><input aria-hidden="true" type="hidden" name="product" value="en/middleware/idm/access-manager/12.2.1.4"></form>
        </div>
        <!--Search results preview-->
        <div id="preview-container" class="preview-hide" style="width: 1161.2px; left: 268px; top: 116px;">
          <!-- No results preview -->
          <div id="no-results-preview" class="preview-hide">
            <div class="no-results-row">
              <span class="no-results-preview-icon" role="presentation"></span>
              <div class="no-results-preview-title">
                No matching results
              </div>
            </div>
            <div class="no-results-preview-text">
              Try a different search query.
            </div>
          </div>
          <!-- Error in results preview -->
          <div id="error-results-preview" class="preview-hide">
            <div class="no-results-row">
              <span class="no-results-preview-icon" role="presentation"></span>
              <div class="no-results-preview-title">
                Search Unavailable
              </div>
            </div>
            <div class="no-results-preview-text">
              We are making updates to our Search system right now. Please try again later.
            </div>
          </div>
          <!-- List search results preview -->
          <div id="results-preview" class="preview-hide">
          </div>
        </div>
        <label id="preview-results-alert" role="alert" aria-live="polite"></label>
        
        <!-- tools -->
        <div class="u02tools" data-trackas="header">
          <ul>
            <!-- user tools -->
            <li class="u02mtool u02accmenu u02toolsloggedout">
              <a role="button" class="u02ticon u02user" aria-label="Account menu, use tab to move through elements">
                <span aria-label="Sign in options" class="u02signin">Sign In</span>
                <span aria-label="Account information and options" class="u02signout">Account</span>
              </a>

              <div class="u02menu-l1z1"><i></i></div><div class="u02user u02toolpop">
                <div class="u02userin">
                  <div class="u02userinw1 u02userloggedin">
                    <div class="u02userinfo">
                      <div class="u02userdata">
                        <a aria-label="First account menu link to navigate to my profile information" class="u02ulink new-window" href="https://profile.oracle.com/myprofile/account/secure/update-account.jspx?nexturl=https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html" target="_blank"> </a>
                      </div>
                    </div>

                    <div class="u02usertools">
                      <div class="u02menucontent">
                        <h5 aria-label="Oracle account options">Oracle Account</h5>
                        <!-- LVL 1 -->
                        <div class="u02menu-l1 u02menuwrap u02menu-nomn" style="">
                          <ul class="u02menu-ul">
                            <li class="u02nosub u02menu-li"><a aria-label="Navigate to my account configurations" id="u02pfile-acct" href="https://profile.oracle.com/myprofile/account/secure/update-account.jspx?nexturl=https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html" data-lbl="account" target="_blank" class="new-window u02xlink">Account</a></li>
                            <li class="u02nosub u02menu-li"><a aria-label="Navigate to Help with your oracle account" href="https://www.oracle.com/corporate/contact/help.html" data-lbl="help" target="_blank" class="new-window u02xlink">Help</a></li>
                            <li class="u02nosub u02menu-li"><a aria-label="Sign out option" href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html#" id="u02pfile-sout" data-lbl="signout" class="u02xlink">Sign Out</a></li>
                          </ul>
                        </div>
                      </div>
                    </div>
                  </div>

                  <div class="u02userinw1 u02userloggedout">
                    <div class="u02usertools">
                      <h5>Oracle Account</h5>
                      <p>Manage your account and access personalized content.
                        <a aria-label="First account menu link to navigate to create a new oracle account" class="u02acclink new-window" href="https://profile.oracle.com/myprofile/account/create-account.jspx" target="_blank">Sign up for an Oracle Account</a>
                      </p>

                      <div class="u02bttn">
                        <a aria-label="Navigate to sign in to my account" href="https://www.oracle.com/webapps/redirect/signon?nexturl=https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html" role="button" id="u02pfile-regs" data-lbl="signin" target="_blank" class="new-window">Sign in to my Account</a>
                      </div>
                    </div>
                  </div>

                  <div class="u02userinw2">
                    <div class="u02usertools">
                      <h5>Sign in to Cloud</h5>
                      <p>Access your cloud dashboard, manage orders, and more.
                        <a aria-label="Navigate to free cloud platform trial" class="u02acclink" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/iaas&amp;id=try-free-tier">Free Cloud Platform Trial</a>
                      </p>

                      <div class="u02bttn">
                        <a aria-label="Last account menu link to navigate to sign in to oracle cloud" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/iaas&amp;id=sign-into-cloud" role="button" data-lbl="signin">Sign in to Cloud</a>
                      </div>

                    </div>
                  </div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <a id="maincontent" tabindex="-1"></a>
    </div>
  </nav>
<!-- /U02v0 -->
</div>
        
                    <main>
                        <div>
                            <div class="ohc-grid">
                                <div>
                                    <div class="ohc-sidebar hidden-xs" role="navigation" style="opacity: 1;">
                                        <form class="ohc-search-form" action="https://docs.oracle.com/apps/search/search.jsp" method="get">
                                            <div class="form-group" id="langselect" aria-label="Select your update">
                                                <div class="input-group">
                                                    <input type="text" class="form-control" name="q" aria-label="Search Query Field" placeholder="Search for...">
                                                    <span class="input-group-btn">
                                                        <button type="submit" class="btn btn-default" aria-label="Submit Search Query">
                                                            <span class="glyphicon glyphicon-search" aria-hidden="true"></span>
                                                            <span class="sr-only">Search</span>
                                                        </button>
                                                    </span>
                                                </div>
                                            </div>
                                            <input type="hidden" name="category" value="middleware">
                                            <input type="hidden" name="product" value="en/middleware/idm/access-manager/12.2.1.4">
                                        </form>
        
                                        <ul class="up">
                                            <li><a href="https://docs.oracle.com/"><span class="glyphicon glyphicon-chevron-left" aria-hidden="true"> </span>Help Center Home</a></li>
                                        </ul>
        
        
                                            
                                            <ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/index.html">Get Started </a>
        
                                                </li>
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/suite/12.2.1.4/idmrn/whats-new-oracle-identity-management-12c-12.2.1.4.0.html#GUID-94F37D95-D734-46C7-9824-079A5D5A9DA0">What's New </a>
        
                                                </li>
                                                <li>  <span>Tasks</span>
        <ul>
            <li class="active">  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html">Install </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/upgrade.html">Upgrade </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/integrate.html">Integrate </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/develop.html">Develop </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/administer.html">Administer </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/monitor.html">Monitor </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/agents.html">Agents </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/sso-and-policies.html">SSO and Policies </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/authentication-and-authorization.html">Authentication and Authorization </a>
        </li>
        </ul>
        
                                                </li>
                                            </ul>
                                            <hr>
                                            <ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/books.html">Books </a>
        
                                                </li>
                                            </ul>
                                            <hr>
                                            <ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/suite/12.2.1.4/tutorials.html">Tutorials </a>
        
                                                </li>
                                            </ul>
                                            <hr>
                                            <ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/rest.html">REST APIs </a>
        
                                                </li>
                                            </ul>
        
                                    </div>
        
                                    <article class="container-fluid learning-path" style="min-height: 857.475px;">
        
                                            <img class="pull-right hidden-xs hidden-sm" src="./Oracle Access Management 12.2.1.4.0 - new_files/3-middleware.png" alt="">
                                            <div class="dropdown pull-right"><button class="btn btn-default" type="button" id="more-menu" data-toggle="modal" data-target="#more-modal">More <span class="caret"></span></button></div><nav aria-label="Breadcrumb" class="breadcrumbNav"><ol class="breadcrumb" vocab="http://schema.org/" typeof="BreadcrumbList">
                                                <li property="itemListElement" typeof="ListItem"><a href="https://docs.oracle.com/index.html" property="item" typeof="WebPage"><span property="name">Home</span></a><meta property="position" content="0"></li>
                                                <li property="itemListElement" typeof="ListItem"><a href="https://docs.oracle.com/en/middleware/index.html" property="item" typeof="WebPage"><span property="name">Middleware</span></a><meta property="position" content="1"></li>
                                                <li property="itemListElement" typeof="ListItem"><a href="https://docs.oracle.com/en/middleware/idm/index.html" property="item" typeof="WebPage"><span property="name">Identity Management (IdM)</span></a><meta property="position" content="2"></li>
                                                <li property="itemListElement" typeof="ListItem"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/index.html" property="item" typeof="WebPage"><span property="name">Access Manager</span></a><meta property="position" content="3"></li>
                                                <li property="itemListElement" typeof="ListItem" class="up"><a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/index.html" property="item" typeof="WebPage"><span property="name">Release 12.2.1.4</span></a><meta property="position" content="4"></li>
                                            </ol></nav>
                                            <h1>Oracle Access Management 12.2.1.4.0</h1>
                                            
                                            
        
        
        
        
        
                                            
                                                <h2 id="Install">Install</h2>
                                            
                                            
                                            
                                            
                                            <div class="description"><p>Documentation for system administrators that describes how to install Oracle Access Management. Learn how to install and configure Oracle Access Management.</p></div>
                                            
                                            <div class="section row" style="visibility: visible;">
                                            
                                                <div class="subsection col-md-6">
                                            
                                            
                                                    <h3>Install Oracle Access Management</h3>
                                            
                                                    <!-- text block -->
                                                    
                                            		<ul class="topics">
                                            			<li>  <a href="https://www.oracle.com/pls/topic/lookup?ctx=en/middleware/idm/access-manager/12.2.1.4&amp;id=GUID-1EAF4522-AACE-4772-9461-85CDBFC862EB">System requirements and certification </a>
                                            </li>
                                            			<li>  <a href="https://www.oracle.com/pls/topic/lookup?ctx=en/middleware/idm/access-manager/12.2.1.4&amp;id=GUID-F81A5C1B-BCE3-4FED-8A3A-8662CC616360">Plan for installation </a>
                                            </li>
                                            			<li>  <a href="https://www.oracle.com/pls/topic/lookup?ctx=en/middleware/idm/access-manager/12.2.1.4&amp;id=GUID-F81A5C1B-BCE3-4FED-8A3A-8662CC616360">Learn about the Oracle Access Management installation </a>
                                            </li>
                                            			<li>  <a href="https://www.oracle.com/pls/topic/lookup?ctx=en/middleware/idm/access-manager/12.2.1.4&amp;id=GUID-B65AA7FB-36C1-42B6-AB7A-05ED4D91F91C">Post installation tasks </a>
                                            </li>
                                            			<li>  <a href="https://www.oracle.com/pls/topic/lookup?ctx=en/middleware/idm/access-manager/12.2.1.4&amp;id=GUID-CDB55063-4BC0-490E-B6E7-6D7B93A35918">Configure Oracle Access Management </a>
                                            </li>
                                            		</ul>
                                            
                                            
                                            
                                                </div>
                                            
                                            
                                            </div>
                                            
        
        
                                    </article>
        
                                    <div><div><!-- resizable column --></div></div>
                                </div>
                            </div>
                        </div>
                    </main>
                    
        
                    <footer role="none"><div role="contentinfo" id="u10" class="u10 u10v0" style="position: relative;" data-trackas="footer"><div class="feedback-widget background"><div class="widget-container">
  <button class="feedback-open" data-toggle="simple-collapsible" href="#feedback-controls" role="button" aria-expanded="false" aria-controls="feedback-controls" aria-label="Open feedback">
  </button>
  <div class="collapse width" id="feedback-controls">
    <button class="feedback-close" type="button" aria-label="Close feedback"></button>
    <span aria-label="Was this page helpful?">Was this page helpful?</span>
    <button class="thumbs down" value="No" aria-label="Open a pop-up to give a feedback about this page for not being helpful"></button>
    <button class="thumbs up" value="Yes" aria-label="Open a pop-up to give a feedback about this page for being helpful"></button>
  </div>
</div>
</div>
  <div class="u10w1">
    <div class="u10w5">
      <ul class="u10-links u10-min">
        <li><a target="_blank" aria-label="Open a new window to © Oracle legal notices" data-lbl="copyright" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/legal&amp;id=cpyr">© Oracle</a></li>
        <li><a target="_blank" aria-label="Open a new window to learn more about oracle" data-lbl="about-oracle" href="https://www.oracle.com/corporate/" class="new-window">About Oracle</a></li>
        <li><a target="_blank" aria-label="Open a new window to contact us oracle" data-lbl="contact-us" href="https://www.oracle.com/corporate/contact/" class="new-window">Contact Us</a></li><li class="u10break"></li>
        <li><a target="_blank" aria-label="Open a new window to products a-z" data-lbl="products-a-z" href="https://docs.oracle.com/en/browseall.html">Products A-Z</a></li>
        <li><a target="_blank" aria-label="Open a new window to read more about oracle terms of use &amp; privacy" data-lbl="terms-of-use-and-privacy" href="https://www.oracle.com/legal/privacy/" class="new-window">Terms of Use &amp; Privacy</a></li>
        <li>
          <div aria-label="Open Cookie Preferences Modal" id="teconsent" consent="undefined" class="truste_caIcon_display" role="complementary"><script async="async" type="text/javascript" crossorigin="" importance="high" src="./Oracle Access Management 12.2.1.4.0 - new_files/v1.7-10255"></script><a role="link" id="icon-id018454313227697106" tabindex="0" lang="en" aria-haspopup="true" aria-label="Cookie Preferences" class="truste_cursor_pointer">Cookie Preferences</a></div>
        </li>
        <li class="u10last"><a target="_blank" aria-label="Open a new window to ad choices" data-lbl="ad-choices" href="https://www.oracle.com/legal/privacy/marketing-cloud-data-cloud-privacy-policy.html#12" class="new-window">Ad Choices</a></li><li class="u10break"></li><li class="last"><a target="_blank" aria-label="Open a new window to © Oracle legal notices" data-lbl="copyright" href="https://docs.oracle.com/pls/topic/lookup?ctx=en/legal&amp;id=cpyr">© Oracle</a></li>
      </ul>
    </div>
  </div>
</div>
</footer>
                </div>

    

<div class="modal" id="videoModal" role="dialog" aria-labelledby="videoModalLabel">
  <div class="modal-dialog modal-lg" role="document">
    <div class="modal-content">
      <div class="modal-header" style="background-color: #000; color: #eee;">
        <button type="button" class="close" style="color: #eee; background-color: #000; opacity: 1;" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
        <div class="modal-title h4" id="videoModalLabel">Video</div>
      </div>
      <div class="modal-body" style="padding: 0px; background-color: #000;">
        <div class="embed-responsive embed-responsive-16by9">
		  <iframe class="embed-responsive-item" src="./Oracle Access Management 12.2.1.4.0 - new_files/saved_resource.html"></iframe>
		</div>
      </div>
    </div>
  </div>
</div><div class="modal" id="more-modal" tabindex="-1" role="dialog" aria-labelledby="more-menu">
  <div class="modal-dialog" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
      </div>
      <div class="modal-body"><ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/index.html">Get Started </a>
        
                                                </li>
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/suite/12.2.1.4/idmrn/whats-new-oracle-identity-management-12c-12.2.1.4.0.html#GUID-94F37D95-D734-46C7-9824-079A5D5A9DA0">What's New </a>
        
                                                </li>
                                                <li>  <span>Tasks</span>
        <ul>
            <li class="active">  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/install.html">Install </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/upgrade.html">Upgrade </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/integrate.html">Integrate </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/develop.html">Develop </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/administer.html">Administer </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/monitor.html">Monitor </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/agents.html">Agents </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/sso-and-policies.html">SSO and Policies </a>
        </li><li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/authentication-and-authorization.html">Authentication and Authorization </a>
        </li>
        </ul>
        
                                                </li>
                                            </ul><hr><ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/books.html">Books </a>
        
                                                </li>
                                            </ul><hr><ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/suite/12.2.1.4/tutorials.html">Tutorials </a>
        
                                                </li>
                                            </ul><hr><ul class="links">
                                                <li>  <a href="https://docs.oracle.com/en/middleware/idm/access-manager/12.2.1.4/rest.html">REST APIs </a>
        
                                                </li>
                                            </ul></div>
    </div>
  </div>
</div>
<script type="text/javascript" src="./Oracle Access Management 12.2.1.4.0 - new_files/notice" id="truste_0.37240516271519963"></script><iframe name="trustarc_notice" id="trustarcNoticeFrame" title="Trustarc Cross-Domain Consent Frame" src="./Oracle Access Management 12.2.1.4.0 - new_files/get.html" style="display: none;"></iframe><script src="./Oracle Access Management 12.2.1.4.0 - new_files/ora_code_docs.js.download"></script><script src="./Oracle Access Management 12.2.1.4.0 - new_files/ora_code.js.download"></script></body></html>
