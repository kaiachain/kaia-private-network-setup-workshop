---
title: "Firewall Configuration"
date: 2022-09-20T17:44:42+09:00
weight: 10
pre: "<b>A. </b>"
draft: false
---
{{< line_break >}}

### 1. *(Only for CN)* Firewall configuration

###### 1) For communication and multichannel between kaia CN, allow TCP ```32323-32324``` with below IP addresses to your firewall ```ingress``` rule.
```vim
CN IPs
Your PN IP
```

###### 2) Additionally, it is required to allow UDP ```32323``` with the same IP addresses to your firewall ```ingress``` rule.
```vim
CN IPs
Your PN IP
``` 

###### 3) For communication, allow ```all traffic``` to your firewall ```egress``` rule.
```vim
IP version    |    Type           |    Protocol    |    Port range    |   Destination
--------------------------------------------------------------------------------------
IPv4          |    All traffic    |    All         |    All           |   0.0.0.0/0
``` 

{{< line_break >}}

### 2. *(Only for PN)* Firewall configuration

###### 1) For communication and multichannel between Kaia PN, allow TCP ```32323-32324``` with below IP addresses to your firewall ```ingress``` rule.
```vim
0.0.0.0/0
```

###### 2) Additionally, it is required to allow UDP ``` 32323 ``` with the same IP addresses to your firewall ```ingress``` rule.
```vim
0.0.0.0/0
``` 

###### 3) For communication, allow ```all traffic``` to your firewall ```egress``` rule.
```vim
IP version    |    Type           |    Protocol    |    Port range    |    Destination
---------------------------------------------------------------------------------------
IPv4          |    All traffic    |    All         |    All           |    0.0.0.0/0
``` 

{{< line_break >}}
{{< line_break >}}

---
{{< line_break >}}

*Please note that the above four IP addresses are attached to the Kaia CNs.*

{{< line_break >}}
{{< line_break >}}
{{< line_break >}}

If you finish this step, please click the next button ```>``` on the right side of this page.
