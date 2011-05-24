openengsb-bundle-1.2.0.RC2_2 2011-05-23
-----------------------------------------

Updating all connectors and domains which include an osgi.bundle file by now and reference to the OpenEngSB Framework 1.3.0.M2. In detail we've updated to Appointment (1.2.1), Build (1.2.1), Contact (1.2.1), Deploy (1.2.1), Notification (1.2.1), Report (1.2.1), Issue (1.2.2), SCM (1.2.1) and Test (1.2.1) Domain. In addition the Email (1.2.1), Google Calendar (1.2.1), Plain Text Report (1.2.1), Prom Report (1.2.1), Git (1.2.2), Maven (1.2.2), Trac (1.2.2), Github Isssues (1.2.1) and Google Contacts (1.2.1) Connectors had been upgraded to their latest Domain versions.

** Library Upgrade
    * [OPENENGSB-1491] - Upgrade openengsb-domain-appointment to 1.2.1
    * [OPENENGSB-1492] - Upgrade openengsb-domain-build to 1.2.1
    * [OPENENGSB-1493] - Upgrade openengsb-domain-contact to 1.2.1
    * [OPENENGSB-1494] - Upgrade openengsb-domain-deploy to 1.2.1
    * [OPENENGSB-1496] - Upgrade openengsb-domain-notification to 1.2.1
    * [OPENENGSB-1497] - Upgrade openengsb-domain-report to 1.2.1
    * [OPENENGSB-1498] - Upgrade openengsb-domain-scm to 1.2.1
    * [OPENENGSB-1499] - Upgrade openengsb-domain-test to 1.2.1
    * [OPENENGSB-1500] - Upgrade openengsb-connector-email to 1.2.1
    * [OPENENGSB-1501] - Upgrade openengsb-connector-gcalendar to 1.2.1
    * [OPENENGSB-1504] - Upgrade openengsb-connector-plaintextreport to 1.2.1
    * [OPENENGSB-1505] - Upgrade openengsb-connector-promreport to 1.2.1
    * [OPENENGSB-1585] - Upgrade openengsb-domain-issue to 1.2.2
    * [OPENENGSB-1586] - Upgrade openengsb-connector-git 1.2.2
    * [OPENENGSB-1587] - Upgrade openengsb-connector-maven to 1.2.2
    * [OPENENGSB-1588] - Upgrade openengsb-connector-trac to 1.2.2
    * [OPENENGSB-1589] - Include openengsb-connector-github-1.2.1
    * [OPENENGSB-1649] - Upgrade openengsb-connector-gcontacts to 1.2.1

** Task
    * [OPENENGSB-1591] - Release openengsb-bundle-1.2.0.RC2_2


openengsb-bundle-1.2.0.RC2_1 2011-05-17
-----------------------------------------

Upgrade karaf, openengsb-root and include the latest openengsb-framework. In addition introduce github connector and minor upgrades/fixes to issue domain and git, maven and trac connector.

** Library Upgrade
    * [OPENENGSB-1488] - Upgrade openengsb-framework to 1.2.0.RC2
    * [OPENENGSB-1495] - Upgrade openengsb-domain-issue to 1.2.1
    * [OPENENGSB-1502] - Upgrade openengsb-connector-git 1.2.1
    * [OPENENGSB-1503] - Upgrade openengsb-connector-maven to 1.2.1
    * [OPENENGSB-1506] - Upgrade openengsb-connector-trac to 1.2.1
    * [OPENENGSB-1572] - Include openengsb-connector-github-1.2.0
    * [OPENENGSB-1582] - Upgrade to openengsb-root-17
    * [OPENENGSB-1596] - Upgrade to karaf-2.2.1

** Task
    * [OPENENGSB-1485] - Release openengsb-bundle-1.2.0.RC2_1


openengsb-bundle-1.2.0.RC1_1 2011-04-30
-----------------------------------------

Initial release of the full openengsb bundle project containing an initial set of plugins and the openengsb-framework

** Bug
    * [OPENENGSB-1352] - Include gcontacts and gcalendar connectors

** Library Upgrade
    * [OPENENGSB-1399] - upgrade to openengsb-root-15
    * [OPENENGSB-1415] - Include openengsb-1.2.0.RC1
    * [OPENENGSB-1421] - Include openengsb-domain-appointment-1.2.0
    * [OPENENGSB-1425] - Include openengsb-domain-build-1.2.0
    * [OPENENGSB-1427] - Include openengsb-domain-contact-1.2.0
    * [OPENENGSB-1429] - Include openengsb-domain-deploy-1.2.0
    * [OPENENGSB-1431] - Include openengsb-domain-issue-1.2.0
    * [OPENENGSB-1433] - Include openengsb-domain-notification-1.2.0
    * [OPENENGSB-1435] - Include openengsb-domain-report-1.2.0
    * [OPENENGSB-1437] - Include openengsb-domain-scm-1.2.0
    * [OPENENGSB-1439] - Include openengsb-domain-test-1.2.0
    * [OPENENGSB-1442] - Include openengsb-connector-email-1.2.0
    * [OPENENGSB-1445] - Include openengsb-connector-gcalendar-1.2.0
    * [OPENENGSB-1448] - Include openengsb-connector-gcontact-1.2.0
    * [OPENENGSB-1451] - Include openengsb-connector-git-1.2.0
    * [OPENENGSB-1456] - Include openengsb-connector-maven-1.2.0
    * [OPENENGSB-1461] - Include openengsb-connector-plaintextreport-1.2.0
    * [OPENENGSB-1463] - Include openengsb-connector-promreport-1.2.0
    * [OPENENGSB-1466] - Include openengsb-connector-trac-1.2.0

** Task
    * [OPENENGSB-1219] - Add new org.openengsb/openengsb-bundle project to bundle the openengsb and the connectors together
    * [OPENENGSB-1242] - create openengsb-bundle
    * [OPENENGSB-1331] - Release openengsb-bundle-1.2.0.RC1_1
    * [OPENENGSB-1410] - Use OpenEngSB NOTICE file

