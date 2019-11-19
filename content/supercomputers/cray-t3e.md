---
title: "Cray T3E Massively Parallel Supercomputer"
date: 2019-11-18T18:33:41+01:00
draft: false
---

## Available Systems

[wildfire.gigaflops.net](#wildfire)
: Air-cooled Cray T3E with 32 PEs, UNICOS/mk 2.0.6 (Unix), 20.0 GigaFLOPS peak performance

[marvel.gigaflops.net](#marvel)
: Air-cooled Cray T3E with 128 PEs, UNICOS/mk 2.0.6 (Unix), 80.0 GigaFLOPS peak performance

## TL;DR

The Cray T3E is the successor of our Cray T3D
and is a massively parallel supercomputer, launched in 1995. In contrast to
our Cray T3D, we own a Cray T3E in a multi-cabinet air-cooled configuration
with up to 128 processing elements. Therefore it's a perfect supercomputer to
run and operate frequently without too complex infrastructure requirements,
except the high power consumption.

Since we have a bunch of cabinets we can even run two Cray T3E
installations! A small configuration with an acceptable power footprint for
regular operation, and a maximum configuration with 128 processors and 16
GBytes of main memory, of course.

The development of massively parallel supercomputers started very early at
Cray. Together with DEC they launched a project called Piranha and the first
results where named Wildfire and Marvel. That's why we named our two
supercomputers wildfire and marvel, too.

If you're interessted in more details about the Cray T3E have a look at
[Wikipedia](https://en.wikipedia.org/wiki/Cray_T3E).

## System Details

### wildfire.gigaflops.net {#wildfire}

This supercomputer should be used as a primary development system for
massively parallel workloads. It consists of two cabinets with 32 processing
elements total. If your code is working fine you can request a schedule for
the larger 128 PEs configuration.

### marvel.gigaflops.net {#marvel}

This supercomputer is the largest possible configuration of an air-cooled
Cray T3E. It consists of 6 cabinets and 128 processing elements total, with a
peak performance of 80.0 GigaFLOPS.
