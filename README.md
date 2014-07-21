_The determination of temperature has long been recognized as a problem of the greatest importance...The theory of thermometry is however as yet far from being in so satisfactory a state._ - [Lord Kelvin, 1848](http://zapatopi.net/kelvin/papers/on_an_absolute_thermometric_scale.html)

kelvin
======

A cool experiment in measuring FISMA compliance

# Hypothesis
DevOps can incorporate security scanning into continuous delivery in a way that improves the security review cycle and shortens time to FISMA compliance.

# Experiment Design
Build an XCCDF (checklist) for some portion of 800-53 guidance applied to NGINX.

# Included Virtual Machines
The `vm` directory includes virtual machines for learning and testing GovReady. 

`vm/basic` provides for a multiple virtual machine environment for testing GovReady. 

`vm/basic/vbkick-templates` provides vbkick virtual machine configuration files for building VirtualBox VM's from source ISO and kick start files.

# Related Readings
[Building a Modern Security Engineering Organization](http://www.slideshare.net/zanelackey/building-a-modern-security-engineering-organization) - Excellent Slideshare by former head of security for Etsy; key lesson is sharing information with everyone and use penetration risks to identify risk patterns not if app is secure.

[DevOpsAudit](http://bit.ly/DevOpsAudit) - Crowd source effort to assemble "authoritative guidance of how management and auditors should conduct audits where DevOps practices are in place"

[Automate Compliance with BDD Tools](http://www.conjur.net/blog/2014/06/30/automate-compliance-with-bdd-tools.html) - A blog post musing on incorporating a security control test from policy into a cucumber test

[Chapter 2 of NIST Special Publication 800-37, Guide for Applying the Risk Management Framework to Federal Information Systems](http://www.nist.gov/customcf/get_pdf.cfm?pub_id=904985) - The official federal fundamentals of managing information security risks and introduction to FISMA's Risk Management Framework (RMF) as whole organization funtion (Chapter 2 starts on page 5)

[Appendix F of  NIST Special Publication 800-53, Security and Privacy Controls for Federal Information Systems and Organizations](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf) - The master catalog of common information systems control (aka, the 800-53's) from which an appropriate subset can be selected and applied to certify a system under the Federal FISMA Risk Management Framework (Appendix F starts on page F-1)


# Related Projects
[OpenSCAP](https://github.com/GovReady/easyscap-output-demo) - Open Source NIST Certified SCAP 1.2 toolkit (on GitHub at https://github.com/OpenSCAP/openscap)

[SSG SCAP Security Guide](https://fedorahosted.org/scap-security-guide/) - security guidance, baselines, and associated validation mechanism; currently supporting SCAP for RHEL6, JBOSS

[GovReady](https://github.com/GovReady/govready) - Toolkit for getting open source apps ready for secure, approved government use (Friendly wrapper around OpenScap)

[FISMA-Ready Ubuntu](https://github.com/fisma-ready/ubuntu-lts) - A hardened baseline guide for Ubuntu LTS versions published by GSA's 18F

[EasySCAP](https://github.com/GovReady/easyscap) - A simple (but equivalent) format for writing SCAP tests by GovReady. Also [EasySCAP Output Demo](https://github.com/GovReady/easyscap-output-demo) for YAML version of SCAP of SCAP-Security-Guide

[Aqueduct](https://fedorahosted.org/aqueduct/) - Attempt to gather together automated changes to RHEL to meet government and Defense Department security compliance; uses bash and puppet.

[NIST Checklist Program](http://checklists.nist.gov) - Official NIST program to promote hardened configuration checklists for software

[Seccubus](http://www.seccubus.com) - "Seccubus runs vulnerability scans at regular intervals and compares the findings of the last scan with the findings of the previous scan. The delta of this scan is presented in a web GUI when findings can be easily marked as either real findings or non-issues. Non issues get ignored until they change. This causes a dramatically reduction a analysis time."

[Gauntlt](http://gauntlt.org) - "Gauntlt provides hooks to a variety of security tools and puts them within reach of security, dev and ops teams to collaborate to build rugged software. It is built to facilitate testing and communication between groups and create actionable tests that can be hooked into your deploy and testing processes."
