# CS19441 - Operating Systems Lab Experiments 🎓💻

Welcome to the CS19441 - Operating Systems Lab Experiments repository! This collection of experiments is designed to deepen your understanding of various operating system concepts and mechanisms. Each experiment focuses on a different aspect of operating systems, from basic installations and configurations to advanced kernel customizations. Below, you'll find a detailed description of each experiment, along with instructions and context to help you get started. Let's dive in! 🚀

## Table of Contents 📚

1. [Installation and Configuration of Linux in a Virtual Machine](#installation-and-configuration-of-linux-in-a-virtual-machine) 🖥️
2. [System Monitoring using Shell Script](#system-monitoring-using-shell-script) 📈
3. [Text Processing using Awk Script](#text-processing-using-awk-script) 📜
4. [User-Defined Signal Handler](#user-defined-signal-handler) 🚦
5. [Trace System Calls with Systrace Tool](#trace-system-calls-with-systrace-tool) 🔍
6. [Inter-Process Communication using Shared Memory](#inter-process-communication-using-shared-memory) 🧩
7. [Scheduling Algorithms](#scheduling-algorithms) 🗓️
8. [Producer-Consumer Problem Solution using Semaphore](#producer-consumer-problem-solution-using-semaphore) 🍞🥛
9. [Banker's Deadlock Avoidance Algorithm](#bankers-deadlock-avoidance-algorithm) 🏦
10. [Contiguous Memory Allocation - First Fit and Best Fit](#contiguous-memory-allocation---first-fit-and-best-fit) 🧠
11. [Page Replacement Algorithms - FIFO & LRU](#page-replacement-algorithms---fifo--lru) 🔄
12. [Customization of Linux Kernel](#customization-of-linux-kernel) 🛠️
13. [Develop a Simple Loadable Kernel Module (LKM)](#develop-a-simple-loadable-kernel-module-lkm) 🧩

## Experiment 1: Installation and Configuration of Linux in a Virtual Machine 🖥️

In this experiment, you will learn how to set up a Linux operating system in a virtual environment. This is a foundational skill that allows you to create a safe and isolated environment for testing and development.

### Steps:
1. **Download and Install VirtualBox**: VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. [Download VirtualBox](https://www.virtualbox.org/) 🌐
2. **Download a Linux Distribution ISO**: Popular choices include Ubuntu, Fedora, and CentOS. [Get Ubuntu](https://ubuntu.com/download) 🌐
3. **Create a New Virtual Machine**:
    - Open VirtualBox and click on "New".
    - Follow the prompts to set up your virtual machine, choosing the downloaded Linux ISO as the startup disk.
4. **Install Linux**: Boot the virtual machine and follow the installation instructions for the chosen Linux distribution.
5. **Post-Installation Configuration**: Configure essential settings such as network, updates, and user management.

By the end of this experiment, you'll have a fully functional Linux system running in a virtual environment, ready for further experimentation. 🎉


## Experiment 2: System Monitoring using Shell Script 📈

Learn to write a shell script to monitor system resources like CPU usage, memory usage, disk usage, and network activity. This script will help in automating the monitoring process and alerting based on certain thresholds. 

## Experiment 3: Text Processing using Awk Script 📜

Explore the powerful text processing capabilities of the `awk` programming language. This experiment involves writing `awk` scripts to perform tasks such as data extraction, reporting, and manipulation.

## Experiment 4: User-Defined Signal Handler 🚦

Understand how to handle signals in Unix-like operating systems by writing a C program that defines custom signal handlers. This experiment demonstrates how signals can be used for inter-process communication and handling unexpected events.

## Experiment 5: Trace System Calls with Systrace Tool 🔍

Use the `systrace` tool to trace and analyze system calls made by a program. This experiment helps in understanding the interaction between user-space applications and the kernel.

## Experiment 6: Inter-Process Communication using Shared Memory 🧩

Implement inter-process communication (IPC) using shared memory. This experiment involves creating a shared memory segment and using it for data exchange between multiple processes.

## Experiment 7: Scheduling Algorithms 🗓️

Implement and compare various CPU scheduling algorithms including:
- First-Come, First-Served (FCFS)
- Shortest Job First (SJF)
- Priority Scheduling
- Round Robin (RR)

## Experiment 8: Producer-Consumer Problem Solution using Semaphore 🍞🥛

Solve the classic producer-consumer problem using semaphores. This experiment demonstrates synchronization techniques to manage concurrent access to shared resources.

## Experiment 9: Banker's Deadlock Avoidance Algorithm 🏦

Implement the Banker's algorithm to avoid deadlocks in a multi-process system. This algorithm helps in ensuring safe resource allocation and avoiding system deadlocks.

## Experiment 10: Contiguous Memory Allocation - First Fit and Best Fit 🧠

Explore memory allocation strategies by implementing the First Fit and Best Fit algorithms. This experiment highlights the trade-offs between different allocation techniques.

## Experiment 11: Page Replacement Algorithms - FIFO & LRU 🔄

Implement and compare the FIFO (First-In-First-Out) and LRU (Least Recently Used) page replacement algorithms. This experiment provides insights into memory management and optimization in operating systems.

## Experiment 12: Customization of Linux Kernel 🛠️

Dive into the world of kernel development by customizing the Linux kernel. This experiment involves downloading the kernel source code, applying patches, and recompiling the kernel.

### Steps:
1. **Download the Kernel Source**: Obtain the latest kernel source code from the official website. [Get Linux Kernel](https://www.kernel.org/) 🌐
2. **Apply Custom Patches**: Modify the kernel code to add new features or improve existing ones.
3. **Compile the Kernel**: Follow the steps to configure and compile the new kernel.
4. **Install and Boot the New Kernel**: Install the compiled kernel and update the bootloader to use it.

This experiment provides a deep understanding of the internals of the Linux kernel and how to modify it to suit specific needs. 🎉


## Experiment 13: Develop a Simple Loadable Kernel Module (LKM) 🧩

Learn to write and load a simple kernel module in Linux. This experiment involves creating a basic LKM, compiling it, and inserting it into the running kernel.

### Steps:
1. **Write the Kernel Module Code**: Create a simple kernel module that prints messages to the kernel log.
2. **Compile the Module**: Use the `make` utility to compile the module.
3. **Insert the Module**: Use the `insmod` command to insert the module into the kernel.
4. **Verify the Module**: Check the kernel log to verify that the module is working correctly.
5. **Remove the Module**: Use the `rmmod` command to remove the module from the kernel.

By the end of this experiment, you'll have a basic understanding of how to extend the functionality of the Linux kernel through modules. 🎉


---

For each experiment, the corresponding code files are provided in this repository. Please navigate to the relevant directories to find the code and additional instructions. 

We hope you find these experiments engaging and educational. Happy coding! 😄👨‍💻👩‍💻
