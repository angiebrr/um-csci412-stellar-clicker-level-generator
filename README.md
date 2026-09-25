# Stellar Clicker Level Generator

> [!WARNING]
> Archived and no longer maintained; kept for reference. Written in 2016 as a NetBeans Java project.

## Overview

A small Java tool that generates level timing tables for [Stellar Clicker](https://github.com/angiebrr/um-csci412-stellar-clicker), a clicker game my team made for CSCI 412 at the University of Montana in spring 2016.

It reads `assets/Configuration/components.json`, which sets a base time and a minimum and maximum level for each ship component, and writes one JSON file per component with how long each level takes. Sample output is in `build/output/`.

**Tech:** Java, json-simple
