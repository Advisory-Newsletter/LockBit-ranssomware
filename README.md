# LockBit-ransomware
**SHA256**
1	0a937d4fe8aa6cb947b95841c490d73e452a3cafcd92645afc353006786aba76
2	0e66029132a885143b87b1e49e32663a52737bbff4ab96186e9e5e829aa2915f
3	0f178bc093b6b9d25924a85d9a7dde64592215599733e83e3bbc6df219564335
4	0f5d71496ab540c3395cfc024778a7ac5c6b5418f165cc753ea2b2befbd42d51
5	13849c0c923bfed5ab37224d59e2d12e3e72f97dc7f539136ae09484cbe8e5e0
6	15a7d528587ffc860f038bb5be5e90b79060fbba5948766d9f8aa46381ccde8a
7	1b109db549dd0bf64cadafec575b5895690760c7180a4edbf0c5296766162f18
8	1e3bf358c76f4030ffc4437d5fcd80c54bd91b361abb43a4fa6340e62d986770
9	256e2bf5f3c819e0add95147b606dc314bbcbac32a801a59584f43a4575e25dc
10	26b6a9fecfc9d4b4b2c2ff02885b257721687e6b820f72cf2e66c1cae2675739
11	2b8117925b4b5b39192aaaea130426bda39ebb5f363102641003f2c2cb33b785
12	3f29a368c48b0a851db473a70498e168d59c75b7106002ac533711ca5cfabf89
13	410c884d883ebe2172507b5eadd10bc8a2ae2564ba0d33b1e84e5f3c22bd3677
14	4acc0b5ed29adf00916dea7652bcab8012d83d924438a410bee32afbcdb995cc
15	5b9bae348788cd2a1ce0ba798f9ae9264c662097011adbd44ecfab63a8c4ae28
16	6292c2294ad1e84cd0925c31ee6deb7afd300f935004a9e8a7a43bf80034abae
17	69d9dd7fdd88f33e2343fb391ba063a65fe5ffbe649da1c5083ec4a67c525997
18	83ab7a2bcac146db472f3b930c01af5b6d3d978ead7b14a9d0ac16e1a76e9f9d
19	9bc98d15f243257c1b5bca59464abe68c680cd5482ba9f5082201dde41a016cf
20	a03326ac8efa930e10091a374d40ddab9f7c2f12246d6ef7983bad93256f1f3a
21	a0085da4a920e92d8f59fefa6f25551655ca911382b5e34df76a9333ac8b7214
22	a08fbf01d02097094b725101309b2bf7fefc2e27724654b840b87e091aa5c9b9
23	a1360645cf3113715cc023d2e4cf9f6f3a6278abcf4499f0ba7cd76c82839eb0
24	c8205792fbc0a5efc6b8f0f2257514990bfaa987768c4839d413dd10721e8871
25	ce8559871b410e23057393eb2d9fb76ec902da2ff1f8006ad312c81852a41f6f
26	e3f236e4aeb73f8f8f0caebe46f53abbb2f71fa4b266a34ab50e01933709e877
27	ec88f821d22e5553afb94b4834f91ecdedeb27d9ebfd882a7d8f33b5f12ac38d
28	ffbb6c4d8d704a530bdd557890f367ad904c09c03f53fda5615a7208a0ea3e4d

**Decryptors**
09e956d140d6879cf7eacbb65dcbfbe1dea1961a31c5d0f834343ef2c886ccc1
9bc98d15f243257c1b5bca59464abe68c680cd5482ba9f5082201dde41a016cf

**VT perks:**
- vhash:"015036656d5223z12z3e05031f1z37z406001a5zb7z"
- imphash:"be232aa2621354bf5dd7b405cc99198c"
-
**Types of LockBit threats**
•	Variant 1 —. abcd extension
•	Variant 2 —. LockBit extension
•	Variant 3 —. LockBit version 2

**Mitigations**
FBI recommends network defenders apply the following mitigations to reduce the risk of compromise by LockBit 2.0 ransomware:

1	Require all accounts with password logins to have strong, unique passwords. Passwords should not be reused across multiple accounts or stored on the system where an adversary may have access.
2	Require multi-factor authentication for all services to the extent possible.
3	Keep all operating systems and software up to date. Prioritize patching known exploited vulnerabilities.
4	Remove unnecessary access to administrative shares, especially ADMIN$ and C$.
5	Use a host-based firewall to only allow connections to administrative shares via server message block (SMB) from a limited set of administrator machines.
6	Enable protected files in the Windows Operating System to prevent unauthorized changes to critical files.
In attack scenarios, attackers use system and network discovery techniques for network and system visibility and mapping.

To limit an attacker from learning the organization’s enterprise environment, limit common system and network discovery techniques by taking the following actions:

1	Segment networks to prevent the spread of ransomware. Network segmentation can help prevent the spread of ransomware by controlling traffic flows between various subnetworks and by restricting adversary lateral movement.
2	Identify, detect, and investigate abnormal activity and potential traversal of the indicated ransomware with a networking monitoring tool.
3	Implement time-based access for accounts set at the admin level and higher. When the account is needed, individual users submit their requests through an automated process that enables access to a system, but only for a set timeframe to support task completion.
4	Disable command-line and scripting activities and permissions. Privilege escalation and lateral movement often depend on software utilities that run from the command line.
5	Maintain offline backups of data, and regularly maintain backup and restoration.
6	Ensure all backup data is encrypted, immutable and covers the entire organization’s data infrastructure.

**Reference**
1	https://www.pcrisk.com/removal-guides/21605-lockbit-2-0-ransomware
2	https://techcommunity.microsoft.com/t5/security-compliance-and-identity/part-1-lockbit-2-0-ransomware-bugs-and-database-recovery/ba-p/3254354
3	https://www.kaspersky.co.uk/resource-center/threats/lockbit-ransomware
4	https://www.trendmicro.com/vinfo/us/security/news/ransomware-spotlight/ransomware-spotlight-lockbit
5	https://www.coveware.com/lockbit-ransomware
6	https://unit42.paloaltonetworks.com/lockbit-2-ransomware/
7	https://geeksadvice.com/remove-lockbit-ransomware-virus/#:~:text=LockBit%20ransomware%20is%20a%20file-encrypting%20virus%20that%20is,or%20.lockbit%20extension%20and%20become%20impossible%20to%20open.
8	https://github.com/sophoslabs/IoCs/blob/master/Ransomware-LockBit
9	https://www.isssource.com/lockbit-2-0-ransomware-iocs-released/
