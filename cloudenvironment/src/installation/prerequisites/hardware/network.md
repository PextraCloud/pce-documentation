# **Network Requirements**

### **Minimum Network Interface Requirements**

- At least **one** 1GbE NIC for basic operations.
- **10GbE or higher** recommended for development and production environments.
- Redundant NICs or **bonded interfaces** are advised for high availability.

### **Use Case-Based Network Recommendations**

| **Use Case**    | **Minimum NIC Speed** | **Recommended NIC Speed** | **Redundancy** |
| --------------- | --------------------- | ------------------------- | -------------- |
| **Testing**     | 1GbE                  | 1GbE                      | Optional       |
| **Research**    | 1GbE                  | 10GbE                     | Recommended    |
| **Development** | 10GbE                 | 25GbE                     | Recommended    |
| **Production**  | 25GbE+                | 40GbE+                    | Required       |

### **Networking Best Practices**

- **Dedicated Management Network:** Isolate **management traffic** from VM traffic.
- **VLAN Segmentation:** Recommended for better security and traffic management.
- **Bonding (LACP/802.3ad):** For increased throughput and redundancy.
- **IPv6 Support:** Ensure compatibility if required in your network setup.
- **Firewalls & Security:** Enable only necessary ports (e.g., **5007** for Pextra web access).
