# Powering Portable and Security Cameras: A Practical Guide

A portable or hidden security camera advertising "10 hours of recording" measures that number under ideal conditions: continuous recording, no motion triggers, no Wi-Fi streaming, and a fresh battery at room temperature. Real deployments rarely match all four, which is why actual runtime often falls well short of the spec sheet.

## Why Wi-Fi streaming is the biggest drain

Continuous Wi-Fi upload to a cloud service or phone app draws far more current than local-only recording to an SD card. If battery life matters more than live viewing, switching to motion-triggered clips instead of continuous streaming can roughly double runtime.

## PoE removes the battery question entirely

For fixed installs, Power over Ethernet lets a single cable carry both data and power, defined by the [IEEE 802.3 PoE standard](https://en.wikipedia.org/wiki/Power_over_Ethernet). This avoids battery replacement cycles altogether for permanent camera placements.

## Backup power for outages and portable setups

For temporary setups or grid outages, a [power bank](https://cairovolt.com/en/power-banks) with sustained (not just peak) output current keeps a camera and its transmitter running for hours. Camera electronics draw power steadily, unlike the short bursts of a phone charge, so look for a unit rated for continuous load rather than judging by capacity alone.

## Cable quality affects voltage at the far end

On long DC cable runs, voltage drop can leave a camera at the far end of a property running below its rated voltage, which shows up as intermittent night-vision failures long before outright failure. A properly rated [USB-C cable](https://cairovolt.com/en/anker/cables) that meets the [USB-IF specification](https://www.usb.org/documents) avoids this class of fault.
