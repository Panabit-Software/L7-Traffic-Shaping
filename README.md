<a name="readme-top"></a>
<h1 align="center">
  <img src="assets/Panabit.png" alt="Panabit" width="240" height="72">
  

  Panabit Intelligent Application Gateway
</h1>


<p align="center">
  <a href="README_CN.md" style="color: #007bff; text-decoration: none; font-weight: bold;">中文</a> | <span style="color: #007bff; font-weight: bold;">English</span>
</p>

---

# 📌 Table of Contents
1. [🌐 Background](#background)
2. [🔥 Challenges of Traditional Traffic Shaping](#challenges-of-traffic-shaping)
3. [🚀 Next-Gen Traffic Shaping: Flexible, Intelligent & Efficient](#next-gen-traffic-shaping)
4. [📌 Case Studies](#case-studies)
5. [⚙️ Basic Configuration](#configuration)
6. [📞 Contact Us](#contact)

---

# 🌐 **Background**  
<a id="background"></a>
In traditional network architectures, traffic shaping typically relies on **static rules** (IP addresses, port numbers, protocol types). While effective in stable environments, these methods face limitations in dynamic networks due to **inflexibility** and **inability to adapt to changing requirements**[2,5](@ref).

---

## 🔥 **Challenges of Traditional Traffic Shaping**  
<a id="challenges-of-traffic-shaping"></a>

### 🔹 **Rigid Architecture**  
- Requires manual updates for IP changes/business expansions  
- High operational costs for rule maintenance[2](@ref)

### 🔹 **Limited Visibility & Control**  
- Cannot identify encrypted traffic or dynamic ports  
- Lacks real-time adjustment based on network status (latency, bandwidth, load)[5](@ref)

---

## 🚀 **Next-Gen Traffic Shaping**  
<a id="next-gen-traffic-shaping"></a>
Our solution enables application-aware traffic management, automatically diverting non-critical applications (e.g., entertainment) to standard lines while maintaining QoS for business-critical traffic[1,6](@ref).

### 🎯 **Multi-Dimensional Matching**  
Supports hybrid matching criteria:
- **Five-tuple** (Source/Destination IP/Port, Protocol)  
- **Application Protocols** (HTTP/HTTPS/DNS)  
- **Domain Patterns** (e.g., `*.tiktok.com`)  
- **VLAN/User Types**[2,6](@ref)

### 🎯 **Precision Identification**  
- **2000+ application protocols** recognition including encrypted P2P/BT/Xunlei  
- Supports MPLS, RSVP, IGRP, BGP, and ICMP analysis[2,5](@ref)  
- Geolocation & ISP attribution for destination IPs  

![Connection Information](assets/Connect_info_EN.png)

### 🎯 **Hybrid Access Modes**  
- **DHCP/Static IP/PPPoE/L2TP** support  
- **100G throughput** with 18M concurrent connections[2,5](@ref)  

---

## 📌 **Case Studies**  
<a id="case-studies"></a>

### **Enterprise Network Optimization**  
#### **Challenge**  
A government service provider faced **500M bandwidth congestion** during peak hours with unstable connectivity.

#### **Solution**  
Deployed Panabit gateway between core and edge switches, implementing:  
- **40% traffic diversion** to mobile networks  
- Application-based QoS prioritization[1,6](@ref)

#### **Results**  
📈 **Performance Improvements**:
- 200M downstream & 100M upstream traffic shifted  
- 40% bandwidth pressure reduction  
- Zero perceptible user experience impact  

![Total Traffic Trends](assets/total_traffic_EN.png)

---

## ⚙️ **Basic Configuration**  
<a id="configuration"></a>

### 🔹 **Traffic Shaping Policy**  
**Path**: `Network Settings > Routing/NAT`  
**Steps**:
1. Create policy with unique ID  
2. Select target protocols (e.g., online games)  
3. Designate NAT line  
4. Deploy configuration[3,6](@ref)

![NAT Configuration](assets/nat_config_EN.png)

### 🔹 **Custom Protocol Setup**  
**Path**: `Application Recognition > Custom Protocols`  
- Define domain/port associations  
- Assign to protocol groups[3,6](@ref)

![Custom Protocol Setup](assets/custom_protocol_step1_EN.png)

---

# 📞 **Contact Us**  
<a id="contact"></a>
🔗 Official Website: [www.panabit.com](https://www.panabit.com/)  
🔗 Technical Forum: [bbs.panabit.com](https://bbs.panabit.com/)  
📧 Support: support@panabit.com  

📞 Contact our solutions team for customized enterprise deployments!
