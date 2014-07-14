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

# Related Readings, Projects
[DevOpsAudit](http://bit.ly/DevOpsAudit) - Crowd source effort to assemble "authoritative guidance of how management and auditors should conduct audits where DevOps practices are in place"

[Automate Compliance with BDD Tools](http://www.conjur.net/blog/2014/06/30/automate-compliance-with-bdd-tools.html) - A blog post musing on incorporating a security control test from policy into a cucumber test

[GovReady](https://github.com/GovReady/govready) - Toolkit for getting open source apps ready for secure, approved government use (Friendly wrapper around OpenScap)

[EasySCAP](https://github.com/GovReady/easyscap) - A simple (but equivalent) format for writing SCAP tests by GovReady. Also [EasySCAP Output Demo](https://github.com/GovReady/easyscap-output-demo) for YAML version of SCAP of SCAP-Security-Guide

[OpenSCAP](https://github.com/GovReady/easyscap-output-demo) - Open Source NIST Certified SCAP 1.2 toolkit (on GitHub at https://github.com/OpenSCAP/openscap)

[SSG SCAP Security Guide](https://fedorahosted.org/scap-security-guide/) - security guidance, baselines, and associated validation mechanism; currently supporting SCAP for RHEL6, JBOSS

[Aqueduct](https://fedorahosted.org/aqueduct/) - Attempt to gather together automated changes to RHEL to meet government and Defense Department security compliance; uses bash and puppet.

[NIST Checklist Program](http://checklists.nist.gov) - Official NIST program to promote hardened configuration checklists for software

[FISMA-Ready Ubuntu](https://github.com/fisma-ready/ubuntu-lts) - A hardened baseline guide for Ubuntu LTS versions published by GSA's 18F

[Gauntlt](http://gauntlt.org) - "Gauntlt provides hooks to a variety of security tools and puts them within reach of security, dev and ops teams to collaborate to build rugged software. It is built to facilitate testing and communication between groups and create actionable tests that can be hooked into your deploy and testing processes."
