# Microsoft cloud services and network security
Microsoft cloud services deliver hyper-scale services and infrastructure, enterprise-grade capabilities, and many choices for hybrid connectivity. Customers can choose to access these services either via the Internet or with Azure ExpressRoute, which provides private network connectivity. The Microsoft Azure platform allows customers to seamlessly extend their infrastructure into the cloud and build multi-tier architectures. Additionally, third parties can enable enhanced capabilities by offering security services and virtual appliances. This white paper provides an overview of security and architectural issues that customers should consider when using Microsoft cloud services accessed via ExpressRoute. It also covers creating more secure services in Azure virtual networks.

## Fast start
The following logic chart can direct you to a specific example of the many security techniques available with the Azure platform. For quick reference, find the example that best fits your case. For expanded explanations, continue reading through the paper.
[![0]][0]

[Example 1: Build a perimeter network (also known as DMZ, demilitarized zone, or screened subnet) to help protect applications with network security groups (NSGs).](#example-1-build-a-perimeter-network-to-help-protect-applications-with-nsgs)</br>
[Example 2: Build a perimeter network to help protect applications with a firewall and NSGs.](#example-2-build-a-perimeter-network-to-help-protect-applications-with-a-firewall-and-nsgs)</br>
[Example 3: Build a perimeter network to help protect networks with a firewall, user-defined route (UDR), and NSG.](#example-3-build-a-perimeter-network-to-help-protect-networks-with-a-firewall-and-udr-and-nsg)</br>
[Example 4: Add a hybrid connection with a site-to-site, virtual appliance virtual private network (VPN).](#example-4-add-a-hybrid-connection-with-a-site-to-site-virtual-appliance-vpn)</br>
[Example 5: Add a hybrid connection with a site-to-site, Azure VPN gateway.](#example-5-add-a-hybrid-connection-with-a-site-to-site-azure-vpn-gateway)</br>
[Example 6: Add a hybrid connection with ExpressRoute.](#example-6-add-a-hybrid-connection-with-expressroute)</br>
Examples for adding connections between virtual networks, high availability, and service chaining will be added to this document over the next few months.
