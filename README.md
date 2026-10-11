# Hash Check

**Hash Check for BTC miners** — a simple health report for your Bitaxe that shows which parts are wearing out, what you can replace yourself, and whether warranty still applies.

## What it does

- Shows a clean, consumer-facing report for a Bitaxe Gamma 601
- Lists every simple-replaceable part (fan, thermal paste, heatsink, PSU, OLED, case)
- Separates parts you can swap yourself from parts that should go back under warranty
- Estimates remaining life on key components based on age, runtime, and usage
- Flags common mods and overclock settings that can void warranty
- Includes built-in explainers so the numbers make sense without technical knowledge

## Demo data

The current version uses real data from a live Bitaxe Gamma 601:

- Purchased December 2024, arrived January 14, 2025 (~21 months old)
- Hashrate, power, temperatures, fan speed, frequency, and voltage pulled from AxeOS
- Pool activity confirmed on Noderunners

## How to view

Live demo: https://hash-check.vercel.app

Or open `index.html` in any modern browser. No install or server required.

## Why it exists

Most mining tools show hashrate and earnings. They don’t tell a regular person when the fan is aging out, when thermal paste should be replaced, or whether the warranty is still valid. Hash Check turns that into a simple health report.

## Hackathon

Built for Crypto World’s Fair (Colosseum).  
A more advanced version (live API, better wear models, repair-shop features) is planned for the Nebius × NVIDIA hackathon.

## License

MIT
