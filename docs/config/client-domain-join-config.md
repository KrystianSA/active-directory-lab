# Domain Join Steps

1. Created CLIENT01 virtual machine inside the same virtual network as DC01

2. Retrieved the private IP address of the Domain Controller

```powershell
ipconfig
```

Example:

```txt
10.0.0.4
```

3. Configured CLIENT01 to use DC01 as the primary DNS server

```txt
10.0.0.4
```

4. Applied the DNS configuration changes on CLIENT01

5. Verified network communication between CLIENT01 and DC01

```powershell
ping 10.0.0.4
```

6. Verified DNS resolution

```powershell
nslookup lab.local
```

7. Joined CLIENT01 to the Active Directory domain

```
lab.local
```

8. Restarted CLIENT01 after successful domain join

9. Added domain users to the:

```
Remote Desktop Users
```

group on CLIENT01

10. Connected to CLIENT01 using domain accounts through RDP

Example:

```txt
LAB\\alice.chen
```

11. Verified successful domain authentication and remote access
