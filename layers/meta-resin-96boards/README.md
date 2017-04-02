# Resin.io layer for meta-96boards supported boards

## Description
This repository enables building resin.io for chosen meta-96boards machines.

## Supported machines
* hikey
* hikey960

## How to?

Q: I generated an image without debug or I downloaded a resin image from the production dashboard. How can I login over serial port?
A: We don't start getty on non debug images. As well there are password changes for root user needed. In order to simplify this process, there is a helper script https://github.com/resin-os/serial-it which does everything for you. Check the help message of that script.