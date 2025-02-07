# **Storage Requirements**

### **Disk Type & Performance Considerations**

The storage system impacts VM performance, clustering, and fault tolerance. Consider the following:

| **Use Case**    | **Minimum Storage** | **Recommended Storage** | **Disk Type**            |
| --------------- | ------------------- | ----------------------- | ------------------------ |
| **Testing**     | 100GB SSD           | 200GB SSD               | SSD                      |
| **Research**    | 200GB SSD           | 500GB NVMe              | SSD/NVMe                 |
| **Development** | 500GB NVMe          | 1TB NVMe RAID           | NVMe                     |
| **Production**  | 1TB NVMe RAID       | 2TB+ Enterprise RAID    | Enterprise SSD/NVMe RAID |

### **Storage Guidelines**

- **NVMe SSDs** are recommended for optimal I/O performance, especially for high-load environments.
- **Dedicated Storage Nodes:** For large-scale deployments, consider using separate storage servers for **scalability** and **high availability**.
