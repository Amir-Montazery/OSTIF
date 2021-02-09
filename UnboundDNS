The project: Unbound DNS

From the Unbound website: “Unbound is a validating, recursive, caching DNS resolver. It is designed to be fast and lean and incorporates modern features based on open standards.To help increase online privacy, Unbound supports DNS-over-TLS which allows clients to encrypt their communication. In addition, it supports various modern standards that limit the amount of data exchanged with authoritative servers. These standards do not only improve privacy but also help making the DNS more robust. The most important are Query Name Minimization, the Aggressive Use of DNSSEC-Validated Cache and support for authority zones, which can be used to load a copy of the root zone.Unbound runs on FreeBSD, OpenBSD, NetBSD, MacOS, Linux and Microsoft Windows, with packages available for most platforms. It is included in the base-system of FreeBSD and OpenBSD and in the standard repositories of most Linux distributions. It is free, open source software under the BSD license.

The Scope

The audit was designed to locate bugs and weaknesses in design that impact the security of servers running Unbound DNS. A combination of manual code auditing, dynamic analysis using a custom fuzzing harness, and static analysis was used to perform the audit.

The Broad Strokes

This project led to a total of 48 changes in unbound that either improve security or fix minor issues that could lead to future security problems as the application grows and evolves over time. The consensus is that Unbound has greatly benefited from the work and that the users and applications that depend on it are now safer than they were prior to our work. A patch was released December 12th 2019. A release candidate patch addressing all outstanding issues is here: https://nlnetlabs.nl/pipermail/unbound-users/2019-December/011930.html all other outstanding issues were corrected in versions 1.9.4 and 1.9.5.

One Critical, Five High, and Five Medium severity issues were found, with an additional 39 issues that were rated as low or informational severity.


Full audit report available for free at: https://ostif.org/our-audit-of-unbound-dns-by-x41-d-sec-full-results/
