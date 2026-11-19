# HTTP Traffic Analysis Using Wireshark

## Overview

This project focuses on understanding and analyzing HTTP communication between a web browser and a web server using Wireshark.

The practical investigation involved capturing HTTP traffic, identifying client requests, analyzing server responses, examining HTTP headers, and reconstructing communication using Follow TCP Stream.

## Objectives

- Understand HTTP communication and its request-response model.
- Learn common HTTP request methods.
- Identify HTTP GET requests and server response codes.
- Examine HTTP request and response headers.
- Understand TCP Stream and its role in packet analysis.
- Practice analyzing HTTP traffic using Wireshark.

## Tools and Environment

- Wireshark 4.6.9
- Google Chrome
- Windows
- Test website: http://info.cern.ch/

## Practical Work

During the investigation, I:

1. Started packet capture in Wireshark.
2. Visited the CERN website using Chrome.
3. Identified the HTTP GET request.
4. Examined the server's HTTP 200 OK response.
5. Analyzed request and response headers.
6. Used Follow TCP Stream to reconstruct and inspect the HTTP conversation.

## Key Findings

- Identified the client and server IP addresses.
- Observed HTTP communication over TCP port 80.
- Analyzed the GET request for the website homepage.
- Identified the server's 200 OK response.
- Examined browser and server HTTP headers.
- Reconstructed the HTTP conversation using TCP Stream.

## Repository Contents

| File | Description |
|---|---|
| HTTP-Analysis.md | Practical HTTP traffic analysis documentation |
| HTTP-Traffic-Analysis-Complete-Notes.md | Detailed HTTP learning notes |
| Screenshots | Evidence of packet capture and analysis |

## Learning Outcome

This project improved my understanding of HTTP request-response communication, common HTTP methods, server response codes, HTTP headers, and TCP Stream analysis.

It also provided practical experience using Wireshark to investigate web traffic from a network security monitoring perspective.
