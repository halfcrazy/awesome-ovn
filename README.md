# Awesome OVN [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome [OVN](https://github.com/ovn-org/ovn) resources

## Official documentation

* [OVN Documentation](https://docs.ovn.org/en/latest/)
* [OVN Manpages](https://www.ovn.org/support/dist-docs)
* [OVN Architecture](https://www.ovn.org/support/dist-docs/ovn-architecture.7.html)

## Blogs and articles

* [OVN: Where is my packet?](http://dani.foroselectronica.es/ovn-where-is-my-packet-665/), by Daniel Álvarez. March 3, 2021
* [Pure L3 OVN dataplane setup](http://dani.foroselectronica.es/pure-l3-ovn-dataplane-setup-652/), by Daniel Álvarez. November 4, 2020
* [OVN external ports](http://dani.foroselectronica.es/ovn-external-ports-604/), by Daniel Álvarez. September 14, 2020
* [Debugging scaling issues on OVN](http://dani.foroselectronica.es/debugging-scaling-issues-on-ovn-595/), by Daniel Álvarez. February 19, 2020
* [OVN Cluster Interconnection](http://dani.foroselectronica.es/ovn-cluster-interconnection-567/), by Daniel Álvarez. February 13, 2020
* [OVN and DHCP: A minimal example](https://blog.oddbit.com/post/2019-12-19-ovn-and-dhcp/), by Lars Kellogg-Stedman. December 19, 2019
* [How to create an Open Virtual Network distributed gateway router](https://developers.redhat.com/blog/2018/11/08/how-to-create-an-open-virtual-network-distributed-gateway-router/), by Numan Siddique. November 8, 2019
* [How to create an Open Virtual Network distributed gateway router](https://numans.blog/2018/11/30/how-to-create-an-open-virtual-network-distributed-gateway-router/), by Numan Siddique. November 30, 2018
* [OVN - Profiling and optimizing ports creation](http://dani.foroselectronica.es/ovn-profiling-and-optimizing-ports-creation-434/), by Daniel Álvarez. February 27, 2018
* [Debugging OVN external connectivity](https://numans.blog/2018/01/05/debugging-ovn-external-connectivity-part-1/), by Numan Siddique. January 5, 2018
* [Native DHCP support in OVN](https://numans.blog/2016/08/09/native-dhcp-support-in-ovn/), by Numan Siddique. August 9, 2016

## Testing and Development

* [ovn-fake-multinode](https://github.com/ovn-org/ovn-fake-multinode) - Easy way to deploy a test cluster. Uses docker-in-docker to emulate a compute node and a vm inside of it
* [vagrants](https://github.com/danalsan/vagrants) - Similar to ovn-fake-multinode but with real VMs. A lot of common usage topologies
* [ovn-heater](https://github.com/dceara/ovn-heater) - Scripts to install/configure/run [ovn-scale-test](https://github.com/ovn-org/ovn-scale-test) on a simulated cluster deployed with ovn-fake-multinode.

## Language bindings
* [libovsdb](https://github.com/ovn-org/libovsdb) - An OVSDB Library written in Go. Can be used to interact with OVN Northbound and Southbound DBs


## Visualization and Troubleshooting

* [ovn_viewer](https://github.com/ralonsoh/ovn_viewer) - A graphical viewer of the NB and SB databases
* [ovnmon](https://github.com/amorenoz/ovnmon) - An OVN database monitoring and introspection tool based on auto-generated schema bindings
