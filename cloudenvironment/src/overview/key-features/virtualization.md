# Virtualization

Virtualization refers to the creation of virtual instances of resources such as compute, storage, and networks. By abstracting these resources from the underlying hardware, virtualization enables more efficient utilization of infrastructure, greater flexibility, and increased scalability. It allows organizations to run multiple operating systems and applications on a single physical machine, optimizing resource allocation and reducing hardware costs.

## Pextra CloudEnvironment® manages virtualization

Pextra CloudEnvironment® offers robust virtualization management capabilities and fully supports **trusted, open-source virtualization technologies**. This ensures that organizations can benefit from flexible, cost-effective solutions while maintaining compatibility with widely-used, reliable technologies.

Pextra CloudEnvironment® integrates and manages the following open-source virtualization tools:

1. QEMU[^1]:
   QEMU (Quick Emulator) is an open-source machine emulator and virtualizer that allows users to run virtual machines (VMs) with different CPU architectures. Pextra CloudEnvironment® integrates QEMU for managing virtual machines, enabling users to run guest operating systems that are isolated and independent of the host machine. QEMU is particularly useful for cross-platform virtualization and emulation.

2. LXC (Linux Containers)[^2]
   LXC provides an OS-level virtualization method for running multiple isolated Linux systems (containers) on a single control host. Pextra CloudEnvironment® fully supports LXC, enabling users to create lightweight, secure containers that share the host kernel but remain isolated from one another. This offers the flexibility of virtualization without the overhead of full virtual machines.

3. Docker®[^3] (Beta):
   Docker® is a popular open-source platform for automating the deployment of applications inside lightweight containers. By using Docker®, Pextra CloudEnvironment® allows users to efficiently deploy, scale, and manage applications in isolated environments, ensuring consistency across different development, testing, and production stages. Docker® containers are portable and fast, making them ideal for microservices architectures and cloud-native applications.

4. Podman[^4]
   Podman is an open-source container engine that facilitates the creation and management of containers without requiring a central daemon. It provides Docker-compatible features but with additional security advantages. Pextra CloudEnvironment® supports Podman to offer users a secure, flexible container solution that can be used alongside or as an alternative to Docker®. Podman operates without requiring root privileges, enhancing container security.

By supporting these trusted open-source technologies, Pextra CloudEnvironment® enables organizations to choose the best virtualization solution for their needs, while ensuring compatibility, security, and efficiency in a rapidly evolving cloud infrastructure.

**Trademarks**
[^1]: QEMU is an open-source project under the GNU General Public License.
[^2]: LXC is an open-source container management technology, widely used in Linux-based systems.
[^3]: Docker® is a registered trademark of Docker, Inc.
[^4]: Podman is an open-source project developed by Red Hat, Inc.
