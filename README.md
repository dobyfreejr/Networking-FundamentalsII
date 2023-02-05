# **In a Network Far, Far Away!**



## *Mission 1*

### **1.Mail servers for starwars.com:**




### **2.Explain why the Resistance isn’t receiving any emails:**

    The resistance isn’t getting emails because their MK aren't set correct for primary and secondary services are provide ie asltx.l.google.com asltx.2.google.com


### **3.Suggested DNS corrections:**

    The corrected DNS should show the following:
    starwars.com mail exchanger = 1 asltx.l.google.com.
    starwars.com mail exchanger = 5 asltx.2.google.com.



## *Mission 2*

### **1.Sender Policy Framework (SPF) of theforce.net:**

    theforce.net	text = "v=spf1 a mx mx:smtp.secureserver.net include:aspmx.googlemail.com ip4:104.156.250.80 ip4:45.63.15.159 ip4:45.63.4.215



### **2.Explain why the Force’s emails are going to spam:**

    The force has not updated their DNS text record to show the required SPF pointer to their recently changed Mail Server to IP 45.23.176.21


### **3.Suggested DNS corrections:**





## *Mission 3*

### **1.Document the CNAME records:**




### **2.Explain why the subpage resistance.theforce.net isn’t redirecting to theforce.net:**

     The DNS CNAME record is missing a reference from resistance.theforce.net to theforce.net


### **3.Suggested DNS corrections:**

    Corrected DNS record should be. www.theforce.net canonical name = theforce.net resistance.theforce.net



## *Mission 4*

### **1.Confirm the DNS records for princessleia.site:**




### **2.Suggested DNS record corrections to prevent the issue from occurring again:**

    Need to add reference to the backup DNS server princessleia.site nameserver = ns25.domiancontrol.com princessleia.site nameserver =ns2.galaxybackup.com



## *Mission 5*

### **1.Document the shortest OSPF path from Batuu to Jedha:**

- #### **OSPF path:**

      Batu D C E F J I L Q T V - Jedha  


- #### **OSPF path cost**

      1 2 1 1 1 1 6 4 2 2 2 —-? 23 hops 



## *Mission 6*

### **1.Wireless key:**





### **2.Host IP addresses and MAC addresses:**

- #### **Sender MAC address:**

      Sender MAC address: Cisco-Li_e3:e4:01 (00:0f:66:e3:e4:01)


- #### **Sender IP address:**

      Sender IP address: 172.16.0.1 (172.16.0.1)


- #### **Target MAC address:**

      Target MAC address: IntelCor_55:98:ef (00:13:ce:55:98:ef)


- #### **Target IP address:**

      Target IP address: 172.16.0.101 (172.16.0.101)


## *Mission 7*

### **1.Screenshot of results:**






