---
title: "SGI Origin 2000 Scalable Shared-Memory Multi-Processing"
date: 2019-11-18T18:33:41+01:00
draft: false
---

## Available Systems

[lego.gigaflops.net](#lego)
: SGI Origin 2000, IRIX 6.5.22f, 3.33 GFlops with 8 procs using -apo -Ofast -O3

## TL;DR

The SGI Origin 2000 is a massively parallel computing system with
shared-memory, launched in 1996. In contrast to other massively parallel
computing systems, developers didn't need to use Message Passing Interface
(MPI) libaries to spread amd organize their workkloads over multiple
processors, especially the main-memory. This task was done in the background
by the NUMAlink (formerly CrayLink) architecture and the system felt like a
huge shared-memory server.

With the help of NUMAlink multiple compute nodes could be wired together
to form a multiprocessor supercomputer. A funny side note is, that the
configuration above 64 processors was sold as the Cray Origin 2000. This
supercomputer supported up to 512 processors, but this configuration was
unsupported and sold only a few times.

During the development of the SGI Origin 2000 the supercomputer had the
  internal code-name Lego.

If you're interessted in more details about the SGI Origin 2000, have a look at
[Wikipedia](https://en.wikipedia.org/wiki/SGI_Origin_2000).

## System Details

### lego.gigaflops.net {#lego}

We wired two 8 processors compute modules with NUMAlink together for a
total of 16 processors and 16 GB main memory.

<table border="1" cellpadding="3">
<thead>
    <tr>
        <th colspan="2" align="left">Specification</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td>Machine Type</td>
        <td>SGI Origin 2000, 2 modules connected via NUMAlink<br>
            Interconnect Bandwidth: 800 MB/s</td>
    </tr>
    <tr>
        <td>Serial #</td>
        <td>Node 1: K0009184<br>
            Node 2: K0016371</td>
    </tr>
    <tr>
        <td>Year of Production</td>
        <td>1997</td>
    </tr>
    <tr>
        <td>CPU Type</td>
        <td>RISC R10000, 250 MHz / 4.0ns, CMOS technology, 4MB Cache</td>
    </tr>
    <tr>
        <td>Number of Processors</td>
        <td>16 cache-coherent NUMA</td>
    </tr>
    <tr>
        <td>Main Memory</td>
        <td>16 GB</td>
    </tr>
    <tr>
        <td>Word Length</td>
        <td>64 bit</td>
    </tr>
    <tr>
        <td>Binary Compatibility</td>
        <td>back to MIPS R3000</td>
    </tr>
    <tr>
        <td>Network Connectivity</td>
        <td>100 MBit/s Ethernet</td>
    </tr>
</tbody>
</table>

<a href="/images/supercomputers/lego_large.jpg" target="blank">
    <img border="2" src="/images/supercomputers/lego_small.jpg">
</a>

