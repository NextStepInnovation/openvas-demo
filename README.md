# Greenbone OpenVAS Demonstration

Today we'll be discussing the OpenVAS vulnerability scanner and its application in enterprise networks. 

This deomonstration is designed to provide you with the tools and background necessary to understand the aim of vulnerability scanning and aid you in testing these technologies yourself.

## Prerequisites:

**Hardware Requirements for Greenbone Community Edition:**

Required:

- CPU Cores: **2**
- Random-Access Memory: **4GB**
- Hard Disk: **20GB free**

Recommended:

- CPU Cores: **4**
- Random-Access Memory: **8GB**
- Hard Disk: **60GB free**

Greenbone OpenVAS is a flexible application that can be built from source or installed within a docker or from pre-built repositories. As we encourage organizations to consider implementing a hardened Kali instance in their network for ease of access to network monitoring tools, and OpenVAS installation is made much simpler through it, our demonstration will be built around Kali.

## Background on OpenVAS


**Greenbone OpenVAS** is an open source, fully-featured vulnerability scanner that can be deployed in a number of different configurations to provide consistent review of the security posture of an enterprise network. One of the distinguishing characteristics of OpenVAS is its inclusion of **Network Vulnerability Tests (NVT's)**. These tests can be ran either individually or collectively as part of a pre-configured scan template. 

## How does OpenVAS work?

All Greenbone Community Edition products are administered from a central server running the **Greenbone Vulnerability Management Daemon (gvmd)**. This is the central service that consolidates plain vulnerability scanning into a full vulnerability management solution. gvmd controls the OpenVAS Scanner via Open Scanner Protocol (OSP). All task scheduling, storage of scan result data and configuration via PostgreSQL, and control of the product's proprietary **Greenbone Management Protocol(GMP)** are facilitated through the gvmd server.

## Installation Walkthrough
[Installation (Kali)](./kali-install.md)

OpenVAS can also be installed via [Greenbone's proprietary Virtual Appliance Solution](https://www.greenbone.net/en/virtual-appliances/), or through [building OpenVAS from source](https://greenbone.github.io/docs/latest/22.4/source-build/index.html)

## Learning the GUI

[Graphical User Interace Walkthrough](./gui-walkthrough.md)

Source: [GeeksForGeeks](https://www.geeksforgeeks.org/installing-openvas-on-kali-linux/)



