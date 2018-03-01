# SAP-Single-VM-Single-NIC-Dual-IP

Based on the "SAP NetWeaver 2-tier compatible template using a Marketplace image" template - https://github.com/Azure/azure-quickstart-templates/tree/master/sap-2-tier-marketplace-image-md/

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsimonhutson%2FSAP-Single-VM-Single-NIC-Dual-IP%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsimonhutson%2FSAP-Single-VM-Single-NIC-Dual-IP%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver, using the latest patched version of the selected operating system. 
This is a template for a 2-tier, 2-nic configuration. It deploys 1 server on Premium Storage.
This template uses Managed Disks.

There is not suitable configuration for X-Large with Standard Storage. If you select this configuration, the template will deploy a Large configuration.

<table>
	<tr>
		<th>Size</th>
		<th>Premium Storage</th>
	</tr>
	<tr>
		<td>Small Hyperthreaded < 2.000 SAPS</td>
		<td>1xDS4s_v3 (2xP20 1xP10)</td>
	</tr>
	<tr>
		<td>Medium Hyperthreaded < 9.000 SAPS</td>
		<td>1xD16s_v3 (3xP20 1xP10)</td>
	</tr>
	<tr>
		<td>Large Hyperthreaded < 18.000 SAPS</td>
		<td>1xD32s_v3 (3xP30 1xP20)</td>
	</tr>
	<tr>
		<td>X-Large Hyperthreaded < 40.000 SAPS</td>
		<td>1xE64s_v3 (4xP30 1xP20)</td>
	</tr>
</table>				
