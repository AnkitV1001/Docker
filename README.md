# Docker

## Understanding Container VS VMs:

### Virtulization Fundamental:

#### VM concept:

<p>Imagine a virtual machine as a complete computer system running within another computer system. It has its own virtual hardware (CPU, RAM, storage), operating system, and applications.</p>

#### Benifits of VMs:

<ul>
  <li>
    <h4>Isolation:</h4>
    Each VM is isolated from other, providing security and stability.
  </li>
 <li>
    <h4>Flexibility:</h4>
   You can run different Operating System on different VMs on the same VM machine.
  </li>
  <li>
    <h4>Portability:</h4>
    VMs can easily moved between different physical machine.
  </li>
</ul>

### Containerization Fundamental:

#### Basic Container concept:

<p>Think of a Container as a lightweight package that include an applications and its dependencies. It shares the host operating system's kernel instead of having its own, making it much smaller and more efficient than a VM.</p>

#### Benifits of Container:

<ul>
  <li>
    <h4>Lightweight:</h4>
    Containers start and stop much faster than VMs due to their smaller size and dependence on Host kernel.
  </li>
 <li>
    <h4>Resource efficiency:</h4>
   Containers use fewer resources than VMs, allowing you to pack more applications on a single machine.
  </li>
  <li>
    <h4>Portability:</h4>
    Containers are self-contained, making them easy to move between different environments.
  </li>
</ul>

### Key Difference

| Feature             | Virtual Machine (VMs) |  Container                   | 
| -------------       | -------------         | ----------                   |
| **Isolation**       | High                  | Low                          |
| **Resource Usages** | High                  | Low                          |         
| **Startup Time**    | Slow                  | Fast                         |
| **Portability**     | High                  | High                         |
| **Flexibility**     | High (Different OS)   | Limited (Shared Limited OS)  |

