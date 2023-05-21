# Docker Cheat Sheet

## Docker

- Docker is an **open-source** platform that enables developers to **automate** the **deployment** and **management** of applications within **software containers**. 
- Containers are lightweight and **isolated** environments that package an application along with its **dependencies**, **libraries**, and **configuration files**. 
- Docker provides a **consistent** and **reproducible** environment across different systems, allowing applications to run reliably and efficiently on any platform that supports Docker. 
- It simplifies the process of software development, testing, and deployment by providing a standardized way to package, distribute, and run applications.

## Containerization

- Containerization is a software development and deployment technique that involves **encapsulating** an application and its dependencies into a **self-contained** unit known as a container. 
- Containers provide a **lightweight** and **isolated environment** that includes the necessary **runtime**, **libraries**, and **files** required to run the application. 
- This isolation ensures that the application can run **consistently** across different computing environments without being affected by the underlying system configurations. 
- Containerization allows for the efficient utilization of resources, simplifies the deployment process, and enables applications to be easily moved between different computing environments, such as development machines, testing environments, and production servers.

## Containerization vs Virtualization

- Containerization and virtualization are two distinct approaches to achieving software isolation and deployment. Here are the key differences between them:
    - **Architecture**: Virtualization involves running multiple virtual machines (VMs) on a physical server, where each VM simulates a complete operating system (OS) along with its own resources, including CPU, memory, storage, and network. In contrast, containerization operates at the OS level, leveraging the host OS to run multiple containers, each isolated and sharing the same OS kernel.
    - **Performance and Resource Utilization**: Virtualization typically requires a hypervisor, which introduces an additional layer of abstraction and can lead to some performance overhead. Containers, on the other hand, have a lighter footprint because they share the host OS and resources, resulting in better performance and higher resource utilization.
    - **Isolation**: Virtual machines offer stronger isolation since each VM has its own complete OS instance, providing a higher level of security and ensuring that one VM cannot interfere with another. Containers provide a lower level of isolation since they share the host OS, making it possible for a compromised container to affect others on the same host.
    - **Portability and Scalability**: Containers are highly portable and can be easily moved between different environments as long as the target system supports the container runtime. Virtual machines can also be moved, but they require more overhead due to the need for a hypervisor. Containers are more lightweight and faster to start and stop, making them ideal for scalability and dynamic resource allocation.
    - **Application Compatibility**: Virtual machines can run a wide range of operating systems, allowing for more flexibility in terms of the applications that can be deployed. Containers, on the other hand, are typically limited to the host OS or compatible OS versions.