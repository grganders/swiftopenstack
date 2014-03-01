swiftopenstack
==============

Swift Install Procedure for Ubuntu 12.04 and Later

This installation procedure use a total of 4 nodes (3 nodes for the Storage Nodes and 1 node for the Proxy), let's call them (<b>swift-proxy-01</b>, <b>swift-node-01</b>, <b>swift-node-02</b> and <b>swift-node-03</b>). The IP address scheme used is the following:

<b>swift-proxy-01</b>:    10.1.1.1 (Public interface)
                          10.2.1.1 (Storage interface)

<b>swift-node-01</b>:     10.1.1.2 (Public interface)
                          10.2.1.2 (Storage interface)

<b>swift-node-02</b>:     10.1.1.3 (Public interface)
                          10.2.1.3 (Storage interface)

<b>swift-node-03</b>:     10.1.1.4 (Public interface)
                          10.2.1.4 (Storage interface)                  

                  
                  
                  
