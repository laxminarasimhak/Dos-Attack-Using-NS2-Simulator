## Dos-Attack-Using-NS2-Simulator

This repository contains the code and documentation for a project that focuses on simulating and Denial of Service (DoS) attacks using NS2, a network simulation tool. The project aims to understand the impact of DoS attacks on network performance and develop effective defense mechanisms to their effects.

## Table of Contents
- [What is DoS attack?](#whatisDoSattack?)
- [What is NS2?](#whatisNS2?)
- [Installation](#installation)
- [How to simulate DoS Attack using NS2?](#howtosimulateDoSAttackusingNS2?)
- [Uses](#uses)
- [References](#references)

## What is DoS attack?
A Denial-of-Service (DoS) attack is an attack meant to shut down a machine or network, making it inaccessible to its intended users. DoS attacks accomplish this by flooding the target with traffic, or sending it information that triggers a crash. In both instances, the DoS attack deprives legitimate users (i.e. employees, members, or account holders) of the service or resource they expected.

## What is NS2?
- NS2 stands for network simulator (version 2). NS2 is a popular network simulation tool used by researchers and network engineers to study and analyze network protocols and behavior.
- NS2 provides substantial support to simulate bunch of protocols like TCP, FTP, UDP, https and DSR.

## Installation
1. Open any linux terminal in your system.
2. Run the following command to update and upgrade your system packages:
3.   sudo apt update
4.   sudo apt upgrade
5. To install NS2, run the the following command
6.   sudo apt install ns2
7. To install Network Animator (NAM),run the following command
8.   sudo apt install nam

## How to simulate DoS Attack using NS2?
To perform a DOS attack simulation using NS2, you will need to:
•	Create a network topology in NS2.(Using udp)
•	Configure the network nodes to simulate the victim and attacker machines.
•	Write a TCL script to launch the DoS attack.
•	Run the simulation using the appropriate NS2 command---ns dos.tcl
•	The results of the simulation can be analyzed to determine the impact of the DoS attack on the victim machine or network.

## Uses
1.	Test the robustness of network applications and services to DoS attacks.
2.	Develop and evaluate DoS attack mitigation techniques.
3.	Educate network administrators and security professionals about DoS attacks and how to respond to DoS attacks.

## References
- https://www.paloaltonetworks.com/cyberpedia/what-is-a-denial-of-service-attack-dos
- https://networksimulator2.com/ns2-ddos-attack/
- https://skillsbuild.edunetworld.com/courses/cs/dos-attack-using-ns2/
- https://www.byos.io/blog/denial-of-service-attack-prevention
