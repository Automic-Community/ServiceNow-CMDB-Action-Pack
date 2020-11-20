*ServiceNow CMDB Action Pack*
=============


Manage ServiceNow Configuration Items (CI)
http://github.com/Automic-Community/ServiceNow-CMDB-Action-Pack

<!-- List of attached files -->
Contents of Solution Package:

						
								*PCK.CUSTOM_SERVICENOW_CMDB_MANAGEMENT_1.0.1.zip
								
								*Action_packcmdb.png
								
						


Documenation and Instructions
---

<p>ServiceNow Configuration Item management<br /><br />This action pack allows you to do basic actions on the CMDB Configuration Items. You can create, update, delete or search for CIs using a selection of fields. Available fields are a selection of the most common fields of the cmdb_ci root table.<br />&nbsp;<br />The action pack is coming with a pre-defined list of more than 100 CI types. You can add you own custom CI types (cmdb tables) by adding records in the VAR Object PCK_CUSTOM_SERVICENOW_CMDB.VAR.CI_TABLES<br /><br />You will find sample workflows in the template folder of the Action Pack that creates a Windows Cluster or a Windows Server, asking the "AUTOMIC" user for the IP Address in order to update the windows server and finally delete the CI.<br />&nbsp;<br /><strong>Pre requisites :</strong><br /><br />The Action pack use the ServiceNow JSONV2 Rest API and requires the Rest Webservice Agent.<br />Tested on ServiceNow Istanbul and One automation 12.0</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
