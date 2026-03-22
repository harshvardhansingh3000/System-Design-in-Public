# System Design in Public

## 📘 Introduction

This repository is a collection of my learnings in system design, documented in a simple and structured way.

The goal is to build a resource that helps me understand concepts better while also making it easier for others to learn system design without feeling overwhelmed. I’ll be continuously adding new topics as I progress.

If you're also learning system design, feel free to explore and use this as a reference.

💡 Contributions are welcome! If you'd like to improve explanations, fix issues, or add new topics, feel free to open a pull request.

---

## 📑 Index

- [What is System Design?](#what-is-system-design)
- [Why is System Design Important?](#why-is-system-design-important)
- [IP (Internet Protocol)](#ip-internet-protocol)
- [IPv4](#ipv4)
- [IPv6](#ipv6)
- [IPv4 vs IPv6](#ipv4-vs-ipv6)

---

## What is System Design?

System design is the process of defining a system’s architecture, components, data flow, and interfaces to meet specific functional and non-functional requirements. It involves identifying how different parts of a system interact with each other to build scalable, reliable, and efficient real-world applications required for business and organizational needs.

---

## Why is System Design Important?

System design is crucial because real-world software systems need to satisfy multiple business and technical requirements. Unlike small or ad-hoc projects, production systems must handle scale, reliability, performance, and maintainability.

Design decisions made in the early stages of development have a significant impact on the overall system. A well-thought-out design helps identify potential issues early, reducing the risk of costly changes later.

If the design is flawed, problems discovered in later stages of development are much more difficult and expensive to fix. This is why investing time in system design upfront is essential for building robust and scalable systems.

---

## IP (Internet Protocol)

IP (Internet Protocol) is a set of rules that defines how data is formatted and transmitted over a network, whether it’s the internet or a local network.

An IP address is a unique identifier assigned to each device on a network. It allows devices to locate and communicate with each other by providing addressing and routing information.

In simple terms, IP addresses help distinguish between different devices such as computers, routers, and servers, enabling data to be sent to the correct destination. They are a fundamental part of how communication happens over the internet.

---

## IPv4

IPv4 (Internet Protocol version 4) is the older version of IP that uses 32-bit addresses to identify devices on a network.

It has a limited number of addresses (~4.3 billion), which led to issues as the internet grew.

---

## IPv6

IPv6 (Internet Protocol version 6) is the newer version designed to solve IPv4 limitations.

It uses 128-bit addresses, providing a massive number of unique addresses and improved features.

---

## IPv4 vs IPv6

| Feature | IPv4 | IPv6 | Explanation |
|--------|------|------|-------------|
| Address Length | Smaller | Much larger | IPv4 has fewer possible addresses, while IPv6 can support a huge number of devices |
| Address Example | 102.22.192.181 | 2001:0db8:85a3:0000:0000:8a2e:0370:7334 | Shows how IPv4 uses only numbers while IPv6 uses numbers and letters |
| Address Format | Numbers with dots | Numbers + letters with colons | IPv6 format allows many more combinations |
| Total Addresses | Limited | Almost unlimited | IPv4 can run out of addresses, IPv6 solves this problem |
| Device Identification | Sometimes shared | Unique for each device | In IPv4, multiple devices may share an address. NAT (Network Address Translation) allows multiple devices in a private network to share a single public IP address. IPv6 gives each device its own unique address |
| Setup | Needs manual setup or DHCP | Can configure itself | IPv6 can automatically assign an address |
| Communication | Sends to many devices (broadcast) | Sends to specific groups (multicast) | IPv6 avoids unnecessary traffic and is more efficient |
| Speed & Efficiency | Older design | More efficient design | IPv6 is optimized for modern networks |
| Usage | Widely used today | Growing usage | IPv4 is common, IPv6 is the future |
