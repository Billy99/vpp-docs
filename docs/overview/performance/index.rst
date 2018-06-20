.. _performance:

=========================================
Performance 
=========================================

Performance Expectations
^^^^^^^^^^^^^^^^^^^^^^^^

One of the benefits of this implementation of FD.io VPP is its high
performance on relatively low-power computing. This high level of
performance is based on the following highlights:

* High-performance user-space network stack for commodity hardware
* The same code for host, VMs, Linux containers
* Integrated vhost-user virtio backend for high speed VM-to-VM connectivity
* L2 and L3 functionality, multiple encapsulations
* Leverages best-of-breed open source driver technology: DPDK
* Extensible by use of plugins
* Control-plane / orchestration-plane via standards-based APIs

Ongoing Regression Performance Tests
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

FD.io VPP platform is high performance packet processing software, typically achieving:

* Multiple MPPS from a single x86_64 core
* >100Gbps full-duplex on a single physical host
* Continuous performance regression testing in FD.io, demonstrates FD.io ongoing commitment to achieving ever performance.

A few examples of test results for FD.io VPP performance data are shown below. 

.. toctree::

    l2ethswitch.rst
    ipv4routedforwarding.rst
    ndr.rst

For More information on CSIT 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

These are FD.io Continuous System Integration and Testing (CSIT)'s documentation links.

* `CSIT Code Documentation <https://docs.fd.io/csit/master/doc/overview.html>`_
* `CSIT Test Overview <https://docs.fd.io/csit/rls1804/report/introduction/overview.html>`_
* `VPP Performance Dashboard <https://docs.fd.io/csit/master/trending/introduction/index.html>`_