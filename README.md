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


## What is Docker?

<ul>
  <li>Docker is a plateform that run containers.</li>
  <li>A container bundles an application's code and all dependencies into one object.</li>
  <li>Containers use less resources than virtual machines.</li>
</ul>

## Why use Docker?

<ul>
  <li>Container easily copied and deployed</li>
  <li>Application that run in containers are segregated from the rest of the host system.</li>
  <li>Containers  are often cheaper to run than VMs.</li>
  <li>Docker containers can be run on plateforms such as AWS, Google Cloud, and other.</li>
</ul>

## What are the docker Downsides?

<ul>
  <li>Not all apps are supported when run in containers.</li>
  <li>Performance can may be sometimes be inconsistent.</li>
  <li></li>
</ul>

## Installing Docker on Ubuntu

```
sudo apt update
```

To check whether docker is running or not.

```
systemctl status docker
```


```
sudo apt install docker.io
```

**If the docker is disable and actively is not running than for enable the docker we use**

```
sudo systemctl enable  docker
```
**And after that check the we can check the status of the Docker**

```
sudo systemctl start docker

```

**For checking the docker run properly or not lets run a text in docker**




