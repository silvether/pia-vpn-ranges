# pia-ranges
A list of all IP blocks used by the Private Internet Access VPN service. Very useful for firewall whitelisting given these are not officially documented.

While I can not be certain that PIA uses all of the IPs in these blocks it is nonetheless useful in minimizing an attack surface.

Possible Use Cases:

1. Deny connections from the PIA service to a website that may experience frequent abuse from VPNs.
2. Limit access to a server resource by only allowing PIA, or even a specific PIA region.
3. Other fun projects..

Please contribute to this list if you can.

Thanks to [jdepalma](https://github.com/jdepalma) for [providing a script](https://github.com/silvether/pia-ranges/blob/master/IPs_022019) that can snag all the most current IPs associated with PIA.
