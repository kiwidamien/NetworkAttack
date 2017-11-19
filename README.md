# Network attack
### Overview
This is a clustering task put together by Kaggle for one of their early competitions. It was uses a version of a dataset created for the 1998 DARPA Intrusion and Detection Evaluation Program.

In this program:
* Lincoln Labs setup a server, and simulated use of the server as a typical US AirForce LAN for 9 weeks
* Over the same 9 weeks, they also tried multiple attacks

The collected about 5 million training records (the first 7 weeks of data) and 2 million test records (the last 2 weeks of data).

Attacks fell into four main categories:
| **Type** | **Description** |
|----|----|
| DOS | Denial-of-service, where the attack is designed to make the server unresponsive because it is too busy dealing with trivial attacks |
| R2L | Unauthorized access from a remote machine (e.g. guessing password)|
| U2R | Unauthorized access to local superuser privilages (e.g. buffer overflows)|
| probing | Surveillance and other probing (e.g. port scanning) | 
