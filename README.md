# AWS Security Labs

Hands-on AWS security labs focused on cloud defense, threat hunting, detection engineering, and secure architecture validation.

This repository contains technical PDF reports documenting practical AWS security scenarios, including defensive architecture, attack simulation, detection logic, monitoring, and lessons learned.

## Purpose

The goal of this repository is to demonstrate practical cloud security skills through documented AWS labs.

Each lab is designed to show:

* the security problem being addressed
* the AWS services involved
* the implemented architecture
* the security controls applied
* the testing or attack simulation performed
* the detection and monitoring approach
* the main findings, limitations, and lessons learned

## Labs

| Lab                             | Topic                                                                             | AWS Services                                                               | Report                                                     |
| ------------------------------- | --------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------- |
| Securing a Web API with AWS WAF | Web application protection, SQL injection mitigation, IP filtering, rate limiting | AWS WAF, API Gateway, Lambda, RDS, CloudWatch                              | [secure_web_app_aws_waf.pdf](./secure_web_app_aws_waf.pdf) |
| AWS Threat Hunting Lab          | DNS exfiltration detection, network inspection, cloud threat hunting              | AWS Network Firewall, Route 53 Resolver DNS Firewall, CloudWatch, Suricata | [Threat Hunting AWS.pdf](./Threat%20Hunting%20AWS.pdf)     |

## Lab 1 — Securing a Web API with AWS WAF

This lab documents the protection of an AWS-based web API using AWS WAF and related cloud-native controls.

### Focus areas

* Web application firewall configuration
* IP allowlisting and filtering
* Rate-based protection
* SQL injection protection
* API Gateway protection
* CloudWatch metrics and visibility
* Defensive validation through controlled testing

### Key security concepts

* Layered application protection
* Managed rule groups
* Input-based attack mitigation
* Basic abuse prevention
* Cloud-native monitoring

## Lab 2 — AWS Threat Hunting Lab

This lab documents a cloud threat hunting scenario focused on suspicious DNS activity and network inspection in AWS.

### Focus areas

* DNS exfiltration detection
* AWS Network Firewall configuration
* Route 53 Resolver DNS Firewall
* Suricata rule logic
* CloudWatch log analysis
* Threat hunting methodology

### Key security concepts

* Network-based detection
* DNS security
* Cloud telemetry analysis
* Detection engineering
* Indicators of compromise
* Defensive investigation workflows

## Skills Demonstrated

This repository demonstrates hands-on experience with:

* AWS security architecture
* Cloud threat hunting
* Detection engineering
* Web application protection
* Network security monitoring
* Security control validation
* CloudWatch-based visibility
* Technical security documentation


## Author

**Sergio Valverde López**

Portfolio: https://sergiovalverde.github.io/
