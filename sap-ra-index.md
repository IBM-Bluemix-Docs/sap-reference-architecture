---

copyright:
  years: 2018, 2020
lastupdated: "2020-05-05"

keywords: SAP Reference Architecture, relational database management systems, RDBMS, SAP Web Dispatcher, SAP NetWeaver Application Servers, application servers, database, high availability, disaster recovery, IBM, IBM Cloud, IBM DB2 LUW, Linux, Red Hat, RHEL, Windows Server, Microsoft SQL Server, SAP HANA, VMware, ESXi, IaaS, Public Cloud, SAP MaxDB, SAP ASE

subcollection: sap-reference-architecture

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# Getting started with IBM Cloud SAP reference architecture
{: #getting-started}

The {{site.data.keyword.cloud}} architecture provides superior technical capabilities, such as a software definable environment critical to a cloud infrastructure, programmable interfaces, and hundreds of hardware and network configurations. It's designed to deliver a higher level of flexibility (by mixing virtual and dedicated servers to fit a variety of workloads), automation of interfaces, and hybrid deployment options. The {{site.data.keyword.cloud_notm}} SAP-Certified Infrastructure offering for SAP HANA and SAP NetWeaver provides you with a best-fit selection. This selection includes bare metal and virtualization-based servers on which the SAP software stack is run.

## Reference architecture
{: #ref-arch}

Figure 1 is a reference architecture (RA) for a landscape comprised of

  * Vyatta network components
  * SAP Web Dispatcher
  * SAP NetWeaver Application Servers
  * SAP HANA databases
  * Other relational database management systems (RDBMS)

The example RA is configured with high availability and disaster recovery. Note that in Figure 1, the database servers can be any database system supported by SAP NetWeaver, for example, SAP HANA.

Figure 1. Sample reference architecture

![Figure 1. Sample reference architecture](/images/SAP-optimization-ref-architecture-20180527.png "Sample reference architecture")
