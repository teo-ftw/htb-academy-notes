# Setting Up

## Introduction

**Important:** Having an organized, efficient and reliable working environment is essential.

### Penetration Testing Stages & Situations

Pentesting can happen either **remotely** or *on-site.**

### Setup & Efficiency

**Important:** Being structured is of paramount importance, because it increases our efficiency in penetration testing.

In this module we will create the essential setup in which we create a working environment for ourselves that we know inside out, can configure ourselves and adapt independently.

## Organization

We organize hosts and servers by their Operating System.

Sample folder structure:

- pre-engagement
- information-gathering
- vulnerability-assesment
- exploitation
- post-exploitation
- lateral-movement
- reporting
- results

We can reorganize the structure based on our field of penetration testing. For example: network pentesting, webapp pentesting, etc.

**Important:** Organizing by OS is more suitable for newcommers and beginners.

### Bookmarks

To keep track of the numerous technologies we will use in our penetration testing journey, we should make a firefox account to sync bookmarks.

**Important:** Do NOT save any bookmarks that could contain sensitive information about a client, considering at some point they could be seen by a third party.

### Password Manager

Problems that passwords create:

1. complexity
2. re-usage
3. remembering

### Updates & Automation

Automation scripts should be used to keep all the technologies we use up to date.

### Note Taking

Information that should be noted down:

1. Newly discovered information (Ip addresses, usernames, passwords, etc.)
2. Ideas for further tests and processing
3. Scan results
4. Logging

**Important:** If third parties attack the company during our penetration test and damage occurs, we can prove that the damage did not result from our activities.

For logging we can use the PS1 variable in order to show our command's date and time.

5. Screenshots (necessary for the Proof-Of-Concept and documentation)

## Virtualization

The main advantage of virtualization is the abstraction layer between the physical resource and the virtual image. 

### Virtual Machines

A virtual machine (VM) is a virtual operating system that runs on a host system (an actual physical computer system).

Benefits:

1. Applications and services of a VM do not interfere with each other
2. Complete independence of the guest system from the host system's operating system and the underlying physical hardware
3. VMs can be moved or cloned to other systems by simple copying
4. Hardware resources can be dynamically allocated via the hypervisor
5. Better and more efficient utilization of existing hardware resources
6. Shorter provisioning times for systems and applications
7. Simplified management of virtual systems
8. Higher availability of VMs due to independence from physical resources

## Linux

**Important:** Linux is the most widely used Operating System for penetration testing.

### Penetration Testing Distributions

The most popular:

1. Kali Linux
2. Black Arch
3. ParrotOS
4. BackBox

**Note:** In the rest of this section I installed ParrotOS on a VirtualBox VM with LUKS encryption.
