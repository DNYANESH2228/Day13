# Day13
Network Traffic Analysis (Wireshark)


## Objective
The goal of this task was to observe real network traffic generated from my system and understand how data travels across a network.

## Tool Used
Wireshark

## Protocol Observed
One of the protocols observed in the packet capture was **DNS (Domain Name System)**.

DNS is responsible for translating domain names like google.com into IP addresses.

## Number of Packets Captured
Approximately **1200+ packets** were captured during a 3-minute capture session.

## Observation
A large number of DNS and TCP packets appeared in a very short time. This shows how frequently systems communicate with servers even when performing simple tasks like opening websites.

## Surprising Finding
Even visiting a single website generated many packets, including DNS requests, TCP connections, and encrypted TLS traffic.

## Why Packet Capture is Sensitive
Packet capture can contain sensitive information such as:

- DNS requests
- Visited websites
- Network communication patterns

Because of this, packet capture should only be performed on networks where you have permission.
