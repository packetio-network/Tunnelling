# Tunnelling
Tunneling is a networking technique that allows the encapsulation of one network protocol within another, enabling the transmission of data packets between networks. It provides a way to create virtual private networks (VPNs), extend networks over long distances, or connect remote networks securely.

## Kernel Network Stack:
The kernel network stack in Linux provides built-in support for various tunneling protocols, including GRE, VxLAN, L2TP, SRv6, and IPSeC. These protocols can be implemented using the kernel's networking subsystem, leveraging its robustness and stability. For example, GRE tunnels can be established using the ip command, while VxLAN can be configured using the ip link command.

## fd.io VPP (Vector Packet Processing):
fd.io VPP is a high-performance, software-based networking stack that provides fast packet processing and advanced tunneling capabilities. It offers support for various tunneling protocols like GRE, VxLAN, L2TP, SRv6, and IPSeC. VPP provides an extensive set of APIs and tools for configuring and managing tunnels, making it an ideal choice for building scalable and efficient tunneling solutions.

## DPDK (Data Plane Development Kit):
DPDK is a set of libraries and drivers that enables fast packet processing in user space. It offers a range of tunneling protocol libraries, including GRE, VxLAN, L2TP, SRv6, and IPSeC. DPDK provides low-level access to network interfaces, allowing for high-performance tunneling implementations with reduced overhead.

## eBPF (Extended Berkeley Packet Filter):
eBPF is a powerful programmable framework that allows for dynamic packet filtering and manipulation. It can be used to implement tunneling protocols like GRE, VxLAN, L2TP, SRv6, and IPSeC through eBPF programs attached to the networking stack. eBPF offers flexibility and extensibility, enabling efficient tunneling solutions with fine-grained control over packet processing.

These implementations provide a range of options for tunneling in networking, each with its own strengths and use cases. Whether using the native kernel stack, leveraging the performance of fd.io VPP and DPDK, or harnessing the programmability of eBPF, network engineers have a diverse toolkit to design efficient and secure tunneling solutions.

## References:
GRE: RFC2784 - https://tools.ietf.org/html/rfc2784
VxLAN: RFC7348 - https://tools.ietf.org/html/rfc7348
L2TP: RFC2661 - https://tools.ietf.org/html/rfc2661
SRv6: RFC8754 - https://tools.ietf.org/html/rfc8754
IPSeC: RFC4301 - https://tools.ietf.org/html/rfc4301
fd.io VPP: https://fd.io/vpp
DPDK: https://www.dpdk.org
eBPF: https://ebpf.io
