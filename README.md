# arm

<a href='https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphiltaylor%2Farm-templates%2Fmaster%2Ftemplate.json'>Deploy template.json</a>
<p>Ingress LB, 2 NGFW, untrust, trust, DMZ, mgmt, egress LB (2 interfaces) - VNET resides in he same RG as NGFW</p>


<a href='https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphiltaylor%2Farm-templates%2Fmaster%2Ftemplate-vnet-rg.json'>Deploy template-vnet-rg.json</a>
<p>Ingress LB, 2 NGFW, untrust, trust, DMZ, mgmt, egress LB (2 interfaces) - VNET resides in different RG to NGFW</p>
<img src="ACC-azure-shared-2.png"/>

<a href='https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphiltaylor%2Farm-templates%2Fmaster%2Ftemplate-vnet-rg-prod-uks.json'>Deploy template-vnet-rg-prod-uks.json</a>
<p>Ingress LB, 2 NGFW, untrust, trust, DMZ, mgmt, egress LB (2 interfaces) - VNET resides in different RG to NGFW</p>

<a href='https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphiltaylor%2Farm-templates%2Fmaster%2Ftemplate-vnet-rg-prod-ukw.json'>Deploy template-vnet-rg-prod-ukw.json</a>
<p>UKW, Ingress LB, 1xNGFW, untrust, trust, mgmt, egress LB (1 interfaces) - VNET resides in different RG to NGFW</p>
<p>removed dmz interfaces and DMZ LB config, removed the protected network and also the vm for deployment</p>

<a href='https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fphiltaylor%2Farm-templates%2Fmaster%2Fazure-uks-feb21.json'>Deploy azure-uks-feb21.json</a>
<p>UKS, Ingress LB, 2xNGFW, untrust, trust, mgmt, egress LB (2 interfaces) - RG selection options</p>
