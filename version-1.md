# A Software Developer&rsquo;s Guide for learning Cyber Security Pathway     :draft:

I&rsquo;ve written up a syllabus for a course that will build a strong foundation for a career as a network engineer and cybersecurity. It is probably a reasonable path to get started but certainly not complete or authorative.

My model is my own study in University, so there&rsquo;s a fair bit of conceptual learning here. There are ways to shift this to be even more hands on, though you will need to learn it all the same. I would like to customize this to your learning style.


<a id="org85d39c5"></a>

## Approach

Learning holistically will make you a better engineer or analyst. Knowing the &rsquo;why&rsquo;, the context, and the history of tools grants you more command over the tools. By knowing what you are doing and why, your solutions will be simpler. It makes your work easier and faster. There&rsquo;s a word used in software sometimes in software: the verb \`grok\` is from Stranger in a Strangeland and means to understand something so completely that it is inseperable from yourself. Grokking then building is the way.

Computer Science and Networking systems are all about information and agreement and managing complexity. Computers and typing aren&rsquo;t as involved as one would think. They&rsquo;re involved in the same way Math is about chalk and greek caligraphy. A surprising amount of the work is thinking and understanding, and some of the best computer scientists are luddites with technology; they hunt and peck to type on ancient PCs. For a practical example, a solution may take me a few weeks to build. On the occasion I lost all my work, it only takes a day or so to recreate from scratch. The work is in understanding and building a mental model.

That is Computer Science which is different than the Software or IT industry. The job is usually to build and change critical systems for a company or organization which demands significantly more typing. Using modern software, running efficient hardware, becoming proficient with tools and streamlining your workflow are part of the work. A senior engineer will outpace a junior, not necessarily because they work quicker, but because they know how to move through the work. This comes over time; you will build muscle memory, an index of patterns and solutions you&rsquo;ve seen, and ability to understand quickly. For learning, your goal is simple: frequent use of tools so you can get comfortable with them.

With all that in mind, this course is split into three parts:

1.  A \`Reading List\` to learn theoretical/concepts and history, building an on
2.  A &rsquo;Practical&rsquo;, a concrete project that would mirror a work assignment
3.  &rsquo;Labs & Tools&rsquo;, smaller exercies and tools to learn & experiment


<a id="org3949d9e"></a>

## Getting Started - Try Hack Me (& Top Down Networking)

You'll have a year subscription to TryHackMe, an online course + exercises for network security without prior knowledge.

Work through the first course, Pre Security. It will cover the basics and the exercises don&rsquo;t require setup. Work through that and some of the other courses, you&rsquo;ll have built a good vocabulary and an orientation to the field.

Once you get far enough to know if you want to learn more, then you can start the Top Down Networking textbook and video lectures in tandem. Pairing the video lecture with the course as you can will balance theory and practice.

> 
> 
> Before hacking something, you first need to understand the basics.
> 
> Cyber security basics
> Networking basics and weaknesses
> The web and common attacks
> Learn to use the Linux operating system
> 
> Introduction
> 
> This learning path will teach you the pre-requisite technical knowledge to get started in cyber security. To attack or defend any technology, you have to first learn how this technology works. The Pre-Security learning path is a beginner friendly and fun way to learn the basics. Your cyber security learning journey starts here!
> 
> Introduction to Cyber Security
> Offensive Security Intro

<https://tryhackme.com/>


<a id="org14e5598"></a>

## Employment + Certifications

I have limited knowledge with this, so take with a grain of salt. Most of this is reading forums and general searching. I have heard that these don&rsquo;t *get* you a job, but are valuable to learn the skills. So keep that in mind when considering spending money on these.

If you&rsquo;re motivated to self learner AND you&rsquo;re building actual projects that hone the skills, certifications are probably not necessary.


<a id="orgeb1311e"></a>

### CompTIA A+


<a id="org2b52d61"></a>

### Step 1.) CompTIA A+ / Net+ / Security+

Entry level more general IT certification.

Some folks suggest skipping, others say it was a great step to learn skills and proceed to

More specialized than the above, but considered a steping stone

This is an entry level certification, so might be an initial goal to target.

-   <https://www.professormesser.com>


<a id="org67f7879"></a>

### Step 2.) Cisco Certifications CCNA

CCNA would be valuable to take when you are starting to interview for netowrking positions. It should help you stand out a bit and ensure you have the skills needed for the position.

Alternatively, you may find a company willing to invest in you earlier. In that case, hopefully, that company might offer education benefits like obtaining the CCNA certificate.

> CCNA or associate level exam just gives bird’s eye view of the networking arena. You would understand the basic level understanding of how the network works and how the packet flow from one laptop to another using different networking devices.


<a id="orge3dd7a3"></a>

### Step 3.) Cisco Intermidiate and Advanced Certificates CCNP / CCIE

Higher level CISCO certification for networking engineering. The general advice I see is to take these after a few years career experience.

> CCNP or professional level exam helps you to get that deep level understanding of the advance networking and by advance, I mean you would get to know how a specific network would behave under specific type arrangement, what could go wrong and what should you do or not do to get out of a situation if things go south.
> 
> All in all, for getting good understanding of the concept, ccnp is good enough and will easily get you inside the company.
> CCIE is the blue whale. This tests you on how in-depth and how good have you played with the networking devices. They will specifically create scenarios which would require you to have intelligence as well as skills to isolate. In CCIE, you would study break and fix scenarios which are tough to crack, once network gets wierd and big.


<a id="org3bffb9e"></a>

## Labs & Tools


<a id="org4eea76d"></a>

### Notes! Blog!

Write everything down and draw it out.

You will remember it better. In this work, you often have to keep track of a lot of details and numbers and ids, and having a stream of notes to refer to can be the difference between solving and not solving a problem.

Additionally, some people are very motivated by publishing and sharing. Starting a small personal blog of your learning path can be a resume builder, a personal achievement and something to look back on.


<a id="org88db85c"></a>

### Linux

Linux is unavoidable for systems and networking. Similar to python, it&rsquo;ll be valuable to become comfortable with. Since it is open source, it is also will give you the most access. Mac/Windows have their own specific tools built on the same concepts, but they are walled gardens and will lock you out of a lot. With Linux, you have access to anything and you could read the source code if you want.

Windows will have its own certification and specializations. It&rsquo;s a viable path but you have to buy into the whole ecosystem. MacOS is built on Unix, so it&rsquo;s closer to what will be on most services, but Apple is interested in making high grade consumer products, so they limit what you can do.


<a id="org987875f"></a>

### Firewalls / Iptables

A firewall is the name of programs that examine network traffic coming in and out of a computer against a list of rules the administrator supplies.

Computers connect to a network and are assigned an IP address, a program on the computer can listen and send data through &rsquo;ports&rsquo;. So for example, port 80 is the most common port for web traffic. So you could setup a computer to listen to port 80 and send the website. You could configure a computer it so only IPs from a &rsquo;whitelist&rsquo; of IPs that are known or safe. Otherwise the response could be rejected or, more traditionally, never respond so it looks like there&rsquo;s no computer on the other end. This gives a potential attacker less information.

\`iptables\` is the name of the most common firewall software for linux, but there are others like \`ipfw\`. Windows and mac have similar solutions.


<a id="orgf8ca98b"></a>

### nmap

\`nmap\` is a command to &rsquo;map&rsquo; a network. It is designed so you can tell it perform a certain action against a range of IPs. So for example, you could join a public wifi network and ask nmap to scan for ports that are responding to requests.

<https://nmap.org/>


<a id="orgfbce5c6"></a>

### Wireshark:

Wireshark is a program that listens to all traffic that it can. Lots of network traffic is broadcast or can be intercepted. It&rsquo;s a good way to see whats going on in a network or what a certain program is sending.

> Wireshark® is a network protocol analyzer. It lets you capture and interactively browse the traffic running on a computer network.

Lab from Top Down Networking: <https://gaia.cs.umass.edu/kurose_ross/wireshark.php>


<a id="org0b1d4b1"></a>

### Tailscale / Wireguard - vpn (virtual private network) software

These are tools to setup a secure &rsquo;private&rsquo; network on top of a public network like the internet.

If you hook up a computer to the internet without firewalls, it will be found and scanned by any number of agents on the internet- from malicious hackers looking for easy targets to companies who are providing some service (google indexes the web to gather the data for its search results).

So one solution is to have firewall rules to lockdown access as much as possible. For example, most home routers reject all internet traffic that wasn&rsquo;t requested. You have to explicitly allow access if you wanted to say connect to a server in the home. There&rsquo;s a balance between security and access. You might have a home server setup so you could access it from work, but

It does a few things, but mainly it is responsbile for creating secret keys + managing access so it can encrypt and decrypt traffic. It sets up firewall rules so that only traffic is accepted from other devices we&rsquo;ve registered on our VPN.

Tailscale is a commercial product around Wireguard.


<a id="org9ee0654"></a>

### Python

Python is a general purpose programming language that is an excellent candidate to become familiar with. It&rsquo;s known as the &rsquo;second best language for everything&rsquo;, there are so many libraries and it so widely used that it will be relevant for decades if not longer.

The syntax is relatively simple and it can be applied to any problem. I often prototype programs in python first, its like a pencil of programming languages.

Having some python knowledge is valuable to any career that involves computers. If you need to automate <span class="underline">anything</span>, python is probably a reasonable candidate.


<a id="orga5cb23b"></a>

### Virtual Machines / Virtualization / Containers

Virtual Machines and Virtualization are common place solutions. Instead of running directly on the hardware, running many smaller computers inside the larger computer allow more efficient and dynamic sharing of resources. A virtual machine or image is a file on a computer, containing all thats needed to run the service. It can be backed up and created as needed.

Virtual Machines are simulating the entire computer to the hardware level, so you could run a windows virtual machine on a mac, even if the architectures are different. Virtualization (or \`Containers\`) simulate the operating system, and the host system hands the container.


<a id="orgcdc168e"></a>

## Reading List


<a id="orgb024981"></a>

### Top Down Networking

A well a well regarded textbook from professors in UMass. I chose it because one of the authors (Crouse) has video lectures + notes for each chapter freely available.

Academic understanding can be irrelevant to the job at hand. Universities are teaching computer science, not how to work in the industry, so the learnings in this book may or may not be relevant to actually trying to get something done. However, learning a topic broadly, in a vaccum has a couple effects:

1.  Expands the solution space- the industry only uses tools that are proven and work, but not necessarily the best solution.
2.  Keeping up to speed - often more academic ideas do get filtered down after a while, so its not uncommon to find a ground breaking new tool based on some academic paper.
3.  Mental expansion - rigorous learning isn&rsquo;t designed to make the specifics stick, but to expand your thinking so that ideas can fit. You build up an ability to mentally swapping and holding concepts and learning quickly.

It can serve as an underpinning.

Notes & Lectures: <https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm>
PDF: <https://github.com/TimorYang/Computer-Networking-Keith-Ross/archive/refs/heads/main.zip>


<a id="org5bf2601"></a>

### Network Programmability and Automation

OReilly is a consistenly good publisher. Partly, I have chose this book to highlight them. This field is about learning, so inevitably, you&rsquo;ll have to find ways to learn. Even in the age of online courses, youtube videos, etc, ther eis no

The second reason is because all roads in software lead to programming. As an information scales, the amount you can accomplish manually becomes a bottleneck. The solution tends to be writing down instructions so that something else can execute it faster, freeing you to work on the harder work.

It&rsquo;s not a new approach: if you run a burger restaurant and needed to serve more customers, you would write down different parts of the work (how to clean at night, recipes, etc.)

With computers, instructions are the code. So in 1995, someone might have been hired to setup a server or two. They bought the hardware, put it in a data center, setup the OS, setup the programs, and would then maintain it. Now we rarely have one server, in fact its standard practice to have multiple in case one falls, and an ability to &rsquo;spin up&rsquo; new servers dynamically when traffic gets heavy. That might happen multiple times a day or hour. Not a task a human could do.

To solve this, we now have programs that can create a server and run the configuration steps automatically. Networking will follow a similar path. For example, at first you might look at logs and notice a particular IP looking for you ports. Or logging and trying various username / password combinations. An admin might open up the firewall rules and add that IP.

Today, that isn&rsquo;t sustainable for even small companies. Since the internet is so populated (by both good and bad actors), the logs would have to be analyzed automatically, examined for threats and the firewalls updated automatically. In fact, most small companies would probably use a product or software built by a specialized company to do accomplish this.

This is the topic Network Programmability and Automation will explore.


<a id="org48c8cfa"></a>

### Network from scratch

One of the best ways to learn how things work is to open them up and find out how they work, then try to create your own implementation.

This is a WIP page that I&rsquo;m including as an example of learning from the ground up. There&rsquo;s a number of &ldquo;\* From Scratch&rdquo; type projects.

<https://www.networksfromscratch.com/>


<a id="org0e36b3c"></a>

## Practicals

The Practical goals can be shaped by you, feel free to modify to suit your goals.


<a id="org9ee0c01"></a>

### The labs from Top Down Networking


<a id="org2beb2a4"></a>

### Setup two computers/laptop with linux for projects


<a id="orgc8f1aad"></a>

### Connect them via a switch and telnet between the two


<a id="orgd3f9cde"></a>

### Write a simple client/server in python


<a id="org28737aa"></a>

### Setup a VPN with tailscale, then wireguard


<a id="org8225b30"></a>

### Setup a network with eero, then ubiquity, then with a linux box.


<a id="orge10844b"></a>

### Split network into vlans


<a id="org5ce4068"></a>

## Outro

That&rsquo;s it for now, but I can keep adding and editing this.

Best wishes on your journey, and I&rsquo;m happy to support however and whenever I can.


