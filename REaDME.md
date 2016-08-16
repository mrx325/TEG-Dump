many companies and analysts rush to figure out what exploits were released, with some already publishing their initial analysis, a few of the highlights based on our cursory examination are below. The directory structure uses four letter code names for specific exploits. Some of the codes, exploit names, and relevant details:

EGBL: EGREGIOUSBLUNDER version 3.0.0.1 – A web-based exploit that targets Fortigate firewalls (various builds of firmware FGT_60-v300) including models 60, 60M, 80C, 200A, 300A, 400A, 500A, 620B, 800, 5000, 1000A, 3600, and 3600A. One researcher notes that Avast calls it CVE-2006-6493, which is a vulnerability in OpenLDAP.

ELBA: ELIGIBLEBACHELOR – An exploit against an unspecified vendor, affecting versions 3.2.100.010, 3.3.001.050, 3.3.002.021 and 3.3.002.030. This exploit uses the third-party library from Keld Simonsen called ISO/IEC 14652 i18n FDCC-set.

ELBO: ELIGIBLEBOMBSHELL version 1.2.0.1 – A web-based exploit reported to be against the Chinese made TOPSEC firewall and affects versions 3.3.005.057.1 to 3.3.010.024.1. Some payloads are noted as having been added as far back as 2009 and have their own code name designations, including WOBBLYLLAMA, FLOCKFORWARD, HIDDENTEMPLE, CONTAINMENTGRID, and GOTHAMKNIGHT. Notes in the exploit include information “FOR DEVELOPERS ONLY”.

ELCA: ELIGIBLECANDIDATE version 1.1.0.1 – A line in the exploit describes itself as “What is the sound of a single thread blocking?” This web-based exploit targets the /cgi/maincgi.cgi script of Chinese made TOPSEC firewalls version 3.3.005.057.1 to 3.3.010.024.1.

ELCO: ELIGIBLECONTESTANT version 1.1.0.1 – A line in the exploit describes itself as “A packet drops in a router. Does anyone hear it?” This web-based exploit targets the /cgi/maincgi.cgi script of Chinese made TOPSEC firewalls before version 3.3. The exploit also has warnings for the user that the “User may be logged in. PLEASE REVIEW SYSTEM INFO“.

EPBA: EPICBANANA version 2.1.0.1 – This exploit targets several models of Cisco PIX Firewalls and Cisco Adaptive Security Appliance (ASA) devices. It uses the pexpect.py Python module written by Noah Spurrier and includes an extensive list of credits for helping develop the module. The affected ASA device images include 711, 712, 721, 722, 723, 724, 80432, 804, 805, 822, 823, 824, 825, 831, and 832. The affected PIX device images include 711, 712, 721, 722, 723, 724, and 804.

ESPL: ESCALATEPLOWMAN version 1.1.0.1 – A local exploit against an unknown vendor, with one very interesting line in the params.py file. One of the configurable parameters is “callback” and the example in the header of the file says “callback       (“30.40.50.60:9342”)  parse to: callback_ip, callback_port”. That IP address is registered to the DoD Network Information Center located in Columbus, Ohio that is part of the Defense Logistics Agency. This may be a telling piece of information, or an unfortunate sample IP address as we see it used in at least one book on administering data centers. One researcher notes that it appears to be unroutable and potentially just a placeholder.

EXBA: EXTRABACON version 1.1.0.1 – An exploit against the SNMP service of Cisco Adaptive Security Appliance (ASA) devices that affects version 8.0(2) to 8.4(4).

The exploit dump contains many other tools and scripts, along with other wonderful codenames such as BANANAGLEE (impacting Juniper devices), BARGLEE, BLATSTING, BUZZDIRECTION, SCREAMPLOW, and BANANADAIQUIRI.
