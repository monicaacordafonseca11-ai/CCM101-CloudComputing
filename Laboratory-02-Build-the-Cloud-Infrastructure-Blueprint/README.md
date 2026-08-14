# Laboratory 02: Build the Cloud Infrastructure

## Mission Overview
In this laboratory mission, I explored how basic cloud systems are built and managed. I used a terminal to log into a remote virtual machine running on a Linux operating system. While connected to the server, I checked its hardware features, studied how major cloud companies organize their services, and created a visual cloud network diagram to show how user traffic flows securely.

## Objectives
* Connect to a remote Linux cloud server using command-line terminal tools.
* Find and record key hardware details such as CPU cores, RAM memory, and hard drive storage.
* Compare essential cloud services across Amazon Web Services, Microsoft Azure, and Google Cloud Platform.
* Draw a simple cloud network diagram that displays how users connect to a cloud server over the internet.

## Cloud Infrastructure Components
* **User (Client):** The person using a web browser or app to request information.
* **Internet:** The public world wide web that carries traffic from the user to the cloud.
* **Virtual Private Cloud (VPC):** A protected private network space inside the cloud where servers run safely.
* **Compute Instance:** The virtual server that runs software code, processes user requests, and executes commands.
* **Cloud Storage:** The persistent hard drive space connected to the server for storing permanent files and data.

## Tools Used
* **Linux Terminal:** A text-based command interface used to connect directly to the cloud server.
* **GitHub:** An online platform used to store, organize, and present project files and documentation.
* **Diagramming Tool:** A visual drawing tool used to create the cloud architecture image.

## Linux Commands Executed
* `lscpu`: Displayed complete details about the central processing unit, including the model name and number of processor cores.
* `free -h`: Displayed the total, used, and available system RAM memory in simple gigabyte and megabyte units.
* `df -h`: Displayed the total capacity and available space on the main disk storage drive in an easy-to-read format.

## Skills Learned
* Logging into and navigating remote Linux virtual servers through command terminal prompts.
* Locating and reading hardware resource details directly from system command outputs.
* Understanding the primary differences and features of major public cloud providers.
* Designing clear cloud infrastructure diagrams to map out network component relationships.

## Challenges Encountered
* **Interpreting Storage Output:** Reading system disk usage from the `df -h` command output was confusing at first because it displayed many temporary system drives on the screen.
* **Solution:** I solved this problem by learning to look specifically for the main root directory line (`/`), which shows the actual hard drive space, and using the `-h` flag to format numbers into clear gigabytes.
* **`reflection.md`**: Outlines personal learning insights, technical challenges faced while reading Linux command outputs, solutions applied to resolve confusion, and key takeaways from the assignment.
* **`screenshots/cloud-architecture.png`**: Displays a clear cloud architecture diagram showing the visual flow of traffic from a user through the public internet into a secure Virtual Private Cloud (VPC) housing compute servers and storage drives.

## Conclusion
This lab successfully demonstrates fundamental skills in cloud resource monitoring, cloud ecosystem research, and basic cloud network topology design.

