Version: NAFATH-V1
Track: Software
##Overview
## Overview

A secure national digital login service depends on six connected technical fields. Software engineering provides the protocols and application logic needed to verify users and authorize access. Artificial intelligence helps identify suspicious login patterns while requiring checks for accuracy, fairness, and security. Mobile development enables citizens to log in safely through smartphone applications. Networking protects DNS queries and supports secure communication between users and servers. Cybersecurity reduces threats such as phishing, account takeover, and unauthorized access. Data management ensures citizens' personal information is collected, stored, and processed responsibly under applicable privacy laws. Together, these fields create a secure, reliable, and privacy-conscious service. A weakness in any field can affect the entire system. Understanding OAuth 2.0 versus OpenID Connect helps software engineers distinguish delegated authorization from user authentication and design safer login processes.
## Software
OAuth 2.0 enables delegated authorization by allowing an application to access protected resources using a scoped access token without receiving the user's password. OpenID Connect builds on OAuth 2.0 by adding an identity layer and an ID token that allows the application to verify the user's identity. Therefore, OAuth 2.0 is used to authorize API access, while OpenID Connect is used to authenticate users during login.

Resource: OpenID Connect Core 1.0 - https://openid.net/specs/openid-connect-core-1_0.html

## AI
Before deploying an AI-based login risk detection system, organisations should assess its validity, reliability, security, resilience, fairness, and privacy risks. They should test false positives and false negatives, evaluate adversarial attacks and data poisoning, and document how decisions are explained and challenged. Clear accountability, human oversight, continuous monitoring, and documented approval criteria help ensure that suspicious-login flags are reliable and that legitimate users can appeal incorrect decisions.

Resource: NIST AI Risk Management Framework (AI RMF 1.0) - https://doi.org/10.6028/NIST.AI.100-1

## Mobile
Android apps run in a sandbox that limits access to other apps' data and protected device features. Normal permissions are generally granted at installation, while dangerous permissions, such as camera and location, require runtime approval. The app must declare the necessary permissions and request them when the user uses a feature that needs access, such as scanning an ID. If permission is denied or revoked, the app should handle this gracefully and offer alternatives where possible.

Resource: Android Developers - Permissions on Android - https://developer.android.com/guide/topics/permissions/overview
