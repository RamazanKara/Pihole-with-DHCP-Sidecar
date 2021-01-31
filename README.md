# Pihole-with-DHCP-Sidecar
 DHCP without exposing the main PiHole Container to the Host Network by exposing it through a sidecar.

## What is this good for?`

If you want to use PiHole but for security reasons or other do not want to expose the whole Container to Host Network. This sets up a separate sidecar which exposes the DHCP Port and connects with the PiHole on a Backend Network. 


## Installation

- Set up Server IP, WebPasswort and run it with Docker-Compose

