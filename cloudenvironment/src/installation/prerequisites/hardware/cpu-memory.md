# **CPU & Memory Requirements**

The performance of **Pextra CloudEnvironment®** heavily depends on the CPU and memory configuration. Below are the recommended specifications based on different use cases.

### **CPU Requirements**

- **Virtualization Support:** The CPU must support **Intel VT-x** or **AMD-V**.
- **Architecture:** x86_64 (64-bit) is required. ARM-based architectures are not currently supported.
- **Multi-Core Performance:** The more cores available, the better the performance in multi-tenant environments.
- **Hyper-Threading:** Recommended for increased efficiency.

#### **Use Case-Based CPU Recommendations**

| **Purpose**     | **CPU Requirement**           | **Hyper-Threading** |
| --------------- | ----------------------------- | ------------------- |
| **Testing**     | 4-core x86_64 (Intel/AMD)     | Optional            |
| **Research**    | 6-core x86_64                 | Recommended         |
| **Development** | 8-core x86_64                 | Recommended         |
| **Production**  | Dual 12-core x86_64 or higher | Required            |

### **Memory (RAM) Requirements**

- **Minimum Requirement:** 8GB RAM (for basic operations).
- **Recommended:** Higher RAM capacity ensures smooth operation of multiple virtual machines (VMs).

#### **Memory Allocation Guidelines**

| **Purpose**     | **Minimum RAM** | **Recommended RAM** |
| --------------- | --------------- | ------------------- |
| **Testing**     | 8GB             | 16GB                |
| **Research**    | 16GB            | 32GB                |
| **Development** | 32GB            | 64GB                |
| **Production**  | 64GB+           | 128GB+              |

- **ECC (Error-Correcting Code) RAM** is highly recommended for stability, especially in production environments.
