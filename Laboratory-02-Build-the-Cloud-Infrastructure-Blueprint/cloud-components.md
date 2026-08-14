Cloud Infrastructure Components

This document outlines the core components that make up our cloud network architecture and explains how data flows through the system.

---

## 1. User (Client)
* **Description:** The end-user accessing the application using a web browser, mobile device, or client application.
* **Function:** Sends incoming requests (such as loading a page or sending data) over secure HTTPS protocols.

## 2. Internet
* **Description:** The public global network connecting the user to the cloud infrastructure.
* **Function:** Acts as the communication bridge, routing traffic securely from the client to the cloud entry point.

## 3. Virtual Private Cloud (VPC)
* **Description:** An isolated, private virtual network space hosted within the cloud provider's platform.
* **Function:** Serves as a security boundary, protecting internal cloud resources (servers and storage) from direct exposure to the public internet.

## 4. Compute Instance (Virtual Machine)
* **Description:** A virtual server running a Linux operating system inside the VPC.
* **Function:** Handles application logic, runs backend software, processes incoming user requests, and executes system commands.

## 5. Cloud Storage
* **Description:** A persistent block or object storage volume attached directly to the compute instance.
* **Function:** Stores long-term project files, system data, and application databases securely so data is not lost when the server restarts.

## 6. Network Interface & IP Configuration
* **Description:** The virtual network card assigned to the cloud server inside the VPC.
* **Function:** Manages local IP addresses, routes data traffic between internal components, and connects the compute server to storage.

---

## Data Flow Summary
1. The **User** sends a request over the **Internet**.
2. Traffic passes into the protected **Virtual Private Cloud (VPC)**.
3. The **Compute Instance** processes the request.
4. Data is retrieved or saved using **Cloud Storage** through the **Network Interface**.
