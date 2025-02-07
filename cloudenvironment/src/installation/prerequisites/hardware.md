# Hardware Requirements

Before installing **Pextra CloudEnvironment®**, ensure your hardware meets the minimum requirements. Requirements vary based on your intended use:

| Purpose         | CPU                 | RAM   | Storage        | Network    |
| --------------- | ------------------- | ----- | -------------- | ---------- |
| **Testing**     | 4-core x86_64       | 8GB   | 100GB SSD      | 1GbE NIC   |
| **Research**    | 6-core x86_64       | 16GB  | 200GB SSD      | 1GbE NIC   |
| **Development** | 8-core x86_64       | 32GB  | 500GB NVMe SSD | 10GbE NIC  |
| **Production**  | Dual 12-core x86_64 | 64GB+ | 1TB NVMe RAID  | 25GbE+ NIC |

### Additional Requirements:

- **UEFI Boot Support**
- **VT-x/AMD-V Enabled** (for virtualization support)
- **Secure Boot Disabled** (if required by Pextra CloudEnvironment)
- **IPMI/iDRAC/iLO** (for remote management, recommended for production)
