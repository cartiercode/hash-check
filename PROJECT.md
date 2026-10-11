# Hash Check — Project Description

**Elevator pitch:** Hash Check for BTC miners.

Hash Check is a simple health report for home Bitcoin miners who lottery mine. It pairs real pool/lottery data with on-device telemetry and a basic node scan so miners can see whether their hardware is healthy, online, and able to reach the Bitcoin network.

## Problem

Solo miners (especially Bitaxe owners) have no easy way to understand the physical health of their hardware. Fans wear out, thermal paste dries, overclocking accelerates aging, and warranties expire. Existing tools are technical and focus on hashrate, not maintenance.

## Solution

A clean, consumer-facing report that:

- Shows current status using real miner data
- Lists every user-replaceable part (no soldering required)
- Separates DIY swaps from warranty/send-away items
- Estimates remaining life on fans and other wear items
- Warns about mods and overclock settings that commonly void warranty
- Includes plain-language explainers so the numbers make sense

## Demo

The submission includes a working single-file demo (`index.html`, live at https://hash-check.vercel.app) populated with real data from a live Bitaxe Gamma 601 (purchased Dec 2024, arrived Jan 2025). Open the file in a browser — no setup required.

## Tech

- Single HTML/CSS/JS file for the MVP
- Real stats from AxeOS + pool history
- Transparent wear estimates based on age, runtime, and usage
- Designed so the same concept can later pull live data or use better models

## Why it matters

It turns a technical device into something a normal person can maintain. The same idea works for other home miners and scales into a useful tool for the growing solo mining community.

**Target:** Crypto World’s Fair (Colosseum)  
**Fallback / next version:** Nebius × NVIDIA Global AI Hackathon
