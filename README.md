# SAP-Single-VM-Single-NIC-Dual-IP

Based on the "SAP NetWeaver 2-tier compatible template using a Marketplace image" template - https://github.com/Azure/azure-quickstart-templates/tree/master/sap-2-tier-marketplace-image-md/

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsimonhutson%2FSAP-Single-VM-Single-NIC-Dual-IP%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fsimonhutson%2FSAP-Single-VM-Single-NIC-Dual-IP%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template takes a minimum amount of parameters and deploys a VM that is customized for use with SAP NetWeaver, using the latest patched version of the selected operating system. 
This is a template for a 2-tier, 1-nic configuration. It deploys 1 server on Premium Storage.
This template uses Managed Disks.

<table>
	<tr>
		<th>Size</th>
		<th>Premium Storage</th>
	</tr>
	<tr>
		<td>ISU</td>
		<td>1xE4s_v3 (1xP6 1xP30 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>CRM</td>
		<td>1xE4s_v3 (1xP6 1xP20 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>PIC</td>
		<td>1xD4s_v3 (1xP6 1xP20 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>BWA</td>
		<td>1xD4s_v3 (1xP6 1xP20 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>MOB</td>
		<td>1xE2s_v3 (1xP6 1xP6 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>EWM</td>
		<td>1xE2s_v3 (1xP6 1xP10 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>JVA</td>
		<td>1xE2s_v3 (1xP6 1xP6 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>CEV</td>
		<td>1xE2s_v3 (1xP6 1xP20 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>PIN</td>
		<td>1xE2s_v3 (1xP6 1xP6 1xP4 1xP6)</td>
	</tr>
	<tr>
		<td>NGW</td>
		<td>1xE2s_v3 (1xP6 1xP10 1xP4 1xP6)</td>
	</tr>
</table>				
