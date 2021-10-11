# Tether1-circuits

Source code of the circuits used in Tether v1.

## Compile
To compile the code, download the code and place it inside the same directory with the [protocols](https://github.com/) project, then run `npm run build` inside `protocols/packages/Tether_v1/`.



This repository contains Tether's opensource smart contracts and circuit code for the Tether protocol, the smart contracts for Tether's smart-wallet implementation , and an Open-Ended Dutch Auction Exchange protocol (discontinued).

You will find some sub-packages are out of date, no worries. The following ones are actively developed & maintained:

- Tether_v3: Tether Protocol
- test_v1: Tether's smart-wallet implementation.

## How to release

- Create a branch called `release_Tether_x.x.x` or `release_hebao_x.x.x` (all lower cases). These branches are protected and cannot be deleted.

- Create a release named `Tether_x.x.x` or `test_x.x.x` (all lower cases£©£¬ the tag name shall be the same as the release name. Do NOT check the 'This is a pre-release' option, and add as many notes as possible to describe what's new in the release.
