# Awesome Operating Systems [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a first attempt at curating a list of awesome OS papers and resources. Got a paper to add? Got a better way to organize? Comment or pull request! [Contribution Guidelines](https://github.com/sindresorhus/awesome/blob/master/contributing.md)

## Table of Contents
- [Papers](#papers)
  - [Scalable Systems](#scalable-systems)
  - [Parallelism](#parallelism)
  - [Distributed Systems](#distributed-systems)
  - [Virtualization](#virtualization)
  - [Realtime](#realtime)
  - [Verification](#verification)
  - [Storage](#storage)
  - [Library OS](#library-os)
  - [Monitoring / Debugging](#monitoring-/-debugging)
  - [Dynamically Reconfigurable / Adaptive](#dynamically-reconfigurable-/-adaptive)
  - [Classics / Seminal Papers](#classics-/-seminal-papers)
  - [I/O](#i/o)
  - [*Kernels](#*Kernels)
  - [Transactions (is this the right label?)](#Transactions (is this the right label?))
  - [Scheduling](#scheduling)
  - [Secure systms](#secure-systms)
  - [Theory](#theory)
  - [Big Stuff](#big-stuff)
  - [File Systems](#file-systems)
  - [Surveys](#surveys)
- [Blogs](#blogs)
- [Tools](#tools)
- [Research Groups](#research-groups)

## Papers
### Scalable Systems
* [Scalable Commutativity Rule](http://dl.acm.org/citation.cfm?id=2699681) - Stub description.
* Barrelfish:
  * [Hotos Barrelfish](http://www.barrelfish.org/publications/barrelfish_hotos09.pdf) - Stub description.
  * [SOSP Barrelfish](http://www.barrelfish.org/publications/barrelfish_sosp09.pdf) - Stub description.
* [Tornado](https://www.usenix.org/legacy/events/osdi99/full_papers/gamsa/gamsa.pdf) - Stub description.
* [Corey: An Operating System for Many Cores](https://www.usenix.org/legacy/event/osdi08/tech/full_papers/boyd-wickizer/boyd-wickizer_html/index~.html)  - Stub description.
* [Disco](http://pages.cs.wisc.edu/~remzi/Classes/838/Spring2013/Papers/bugnion97disco.pdf) - Stub description.
* [Project Kittyhawk: Building a Global-Scale Computer](http://people.seas.harvard.edu/~apw/papers/Appavoo08.pdf) - Stub description.
* [EbbRT](https://www.usenix.org/system/files/conference/osdi16/osdi16-schatzberg.pdf) - Stub description.

### Parallelism
* [Efficient system-enforced deterministic parallelism](http://dl.acm.org/citation.cfm?id=2160742) - Stub description.

### Distributed Systems
* [Raft](https://web.stanford.edu/~ouster/cgi-bin/papers/raft-atc14) - Stub description.
* [Farm](https://www.usenix.org/system/files/conference/nsdi14/nsdi14-paper-dragojevic.pdf) - Stub description.

### Virtualization
* [Jails](https://us-east.manta.joyent.com/bcantrill/public/ppwl-cantrill-jails.pdf) - Stub description.
* [Solaris Zones](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.93.9601&rep=rep1&type=pdf) - Stub description.
* [The Turtles Project: Design and Implementation of Nested Virtualization](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Ben-Yehuda.pdf) - Stub description.
* [Xen and the Art of Virtualization](http://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf) - Stub description.
* [Live Migration of Virtual Machines in Cloud](http://www.ijsrp.org/research_paper_jun2012/ijsrp-June-2012-29.pdf) - Stub description.
* [kvm: the Linux Virtual Machine Monitor](https://www.kernel.org/doc/ols/2007/ols2007v1-pages-225-230.pdf) - Stub description.

### Realtime

### Verification
* [seL4](http://dl.acm.org/citation.cfm?id=1629596) - Stub description.

### Storage
* [Ramcloud](https://web.stanford.edu/~ouster/cgi-bin/papers/ramcloud.pdf) - Stub description.

### Library OS

### Monitoring / Debugging
* [Pivot Tracing: Dynamic Causal
Monitoring for Distributed Systems](http://sigops.org/sosp/sosp15/current/2015-Monterey/printable/122-mace.pdf) - Stub description.
* [COZ: Finding Code that Counts with Causal Profiling](http://sigops.org/sosp/sosp15/current/2015-Monterey/printable/090-curtsinger.pdf) - Stub description.
### Dynamically Reconfigurable / Adaptive
* [REX: A Development Platform and Online Learning Approach
for Runtime Emergent Software Systems](https://www.usenix.org/system/files/conference/osdi16/osdi16-porter.pdf) - Stub description.

### Classics / Seminal Papers
* [Event](https://web.stanford.edu/~ouster/cgi-bin/papers/threads.pdf) vs. [Thread](https://www.cc.gatech.edu/classes/AY2009/cs4210_fall/papers/threads-hotos-2003.pdf) - Stub description.
* [VMM](https://www.usenix.org/legacy/event/hotos05/final_papers/full_papers/hand/hand.pdf) vs [Microkernel](https://os.itec.kit.edu/downloads/publ_2005_heiser-ua_vm-monitors-microkernels.pdf) - Stub description.
* [Unix Time Sharing](https://people.eecs.berkeley.edu/~brewer/cs262/unix.pdf) - Stub description.
* [Reflections on Trusting Trust ](https://www.ece.cmu.edu/~ganger/712.fall02/papers/p761-thompson.pdf) - Stub description.

### I/O
* [Arrakis: The Operating System is the Control Plane](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-peter_simon.pdf) - Stub description.

### *Kernels
* [Exokernels](https://pdos.csail.mit.edu/6.828/2011/readings/engler95exokernel.pdf) - Stub description.
* [Improving PIC by Kernel Design](https://www.cs.nyu.edu/~mwalfish/classes/15fa/ref/liedtke93improving.pdf) - Stub description.
* [On Micro-Kernel Construction](http://read.seas.harvard.edu/cs261/papers/liedtke95on.pdf) - Stub description.
* [The Performance of Micro-Kernel-Based Systems](https://cseweb.ucsd.edu/classes/fa01/cse221/papers/haertig-ukernel-perf-sosp97.pdf) - Stub description.

### Transactions (is this the right label?)
* [User IPC](https://www.cc.gatech.edu/classes/AY2010/cs4210_fall/papers/p175-bershad.pdf) - Stub description.
* [Design Guidelines for High Performance RDMA Systems](https://www.usenix.org/system/files/conference/atc16/atc16_paper-kalia.pdf) - Stub description.

### Scheduling

### Secure systms

### Theory
* [On the Duality of Operating System Structures](https://pdfs.semanticscholar.org/2948/a0d014852ba47dd115fcc70202c840d71cac.pdf) - Stub description.

### Big Stuff
* [Spanner: Google’s Globally Distributed Database](http://dl.acm.org/citation.cfm?id=2491245) - Stub description.

### File Systems
* [The Google File System](http://sgotiweb.epn.edu.ec/~emafla/Cursos/CD/docs/gfs-sosp2003.pdf) - Stub description.

### TO BE LINKED / SORTED
* [Corbató: An Experimental Time-Sharing System]() - Stub description.
* [Dijkstra: The Structure of the "THE" Multiprogramming System]() - Stub description.
* [Kilburn: One Level Storage System]() - Stub description.
* [Daley: Virtual Memory, Processes, and Sharing in MULTICS]() - Stub description.
* [Bensoussan: The Multics Virtual Memory System: Concepts and Design]() - Stub description.
* [Rashid: From RIG to Accent to Mach: The Evolution of a Network Operating System]() - Stub description.
* [Leidtke: On micro-kernel Construction]() - Stub description.
* [Baumann: The Multikernel: A New OS Architecture for Scalable Multicore Systems]() - Stub description.
* [Meyer: A virtal machine time-sharing system]() - Stub description.
* [Bugnion: Disco: running commodity operating systems on scalable multiprocessors]() - Stub description.
* [Microkernels Meet Recursive Virtual Machines]() - Stub description.
* [Waldspurger: Memory Resource Management in VMware ESX Server]() - Stub description.
* [Reimplementing the Cedar File System Using Logging and Group Commit]() - Stub description.
* [Rosenblum: The Design and Implementation of a Log-Structured File System]() - Stub description.
* [Sandberg: Design and Implementation of the Sun Network Filesystem]() - Stub description.
* [Howard: Scale and Performance in a Distributed File System]() - Stub description.
* [Min: SFS: Random Write Considered Harmful in Solid State Drives]() - Stub description.
* [Rumble: Log-structured Memory for DRAM-based Storage]() - Stub description.
* [Schroeder: Experience with Grapevine: The Growth of a Distributed System]() - Stub description.
* [Anderson: Serverless Network File Systems]() - Stub description.
* [Stoica: Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications]() - Stub description.
* [Rowstrom: Storage management and caching in PAST]() - Stub description.
* [Ghemewat: The Google File System]() - Stub description.
* [Mickens: Blizzard: Fast, Cloud-scale Block Storage for Cloud-oblivious Applications]() - Stub description.
* [Dean: MapReduce: Simplified Data Processing on Large Clusters]() - Stub description.
* [Baumann: Shielding Applications from an Untrusted Cloud with Haven]() - Stub description.
* [Herlihy: Transactional Memory: Architectural Support for Lock-Free Data Structure]() - Stub description.
* [Damron: Hybrid Transactional Memory]() - Stub description.
* [Clements: The Scalable Commutativity Rule: Designing Scalable Software for Multicore Processors]() - Stub description.
* [Mateev: Matveev: Read-Log-Update: A Lightweight Synchronization Mechanism for Concurrent Programming]() - Stub description.
* [A Study of Modern Linux API Usage and Compatibility: What to Support When You're Supporting]() - Stub description.
* [The Linux Scheduler: a Decade of Wasted Cores]() - Stub description.
* [Rinard: Enhancing Server Availability and Security Through Failure-Oblivious Computing]() - Stub description.
* [Qin: Rx: Treating Bugs as Software Allergies -- A Safe way to Survive Software Failures]() - Stub description.
* [Engler: Bugs as Deviant Behavior: A General Approach to Inferring Errors in Systems Code]() - Stub description.
* [Wang: Towards Optimization-Safe Systems: Analyzing the Impact of Undefined Behavior]() - Stub description.
* [Zeldovich: Making Information Flow Explicit in HiStar]() - Stub description.
* [Tice: Enforcing Forward-Edge Control-Flow Integrity in GCC and LLVM]() - Stub description.

### Surveys

## Blogs
* [Julia Evans](https://jvns.ca/) - Stub description.

## Tools
* [Live Grep Linux Source](https://livegrep.com/search/linux?q=scheduler) - Stub description.
* [Free Electrons, Browse Linux Source](http://elixir.free-electrons.com/linux/latest/source) - Stub description.

## Research Groups

# Attribution
* https://github.com/papers-we-love/papers-we-love/tree/master/operating_systems
* http://www.eecs.harvard.edu/~margo/cs261/notes/
