# sagebrush_hardware
Hardware designs associated with the SageBRUSH system

The SageCamv1.0 with SageMic add-on and Nanobeam connectivity has the most thorough documentation with an
instruction manual from building to deploying. We are actively working on documentation for the other
hardware builds, but currently, that unit is the best place to start.

If you happen to build one of our systems, please let us know! We'd love to hear whether the documentation was
thorough enough for you to follow along or if it needs more detail in specific sections. We'd appreciate feedback
in the form of issues in the issue tracker.

The software repo and infrastructure set-ups assosicated with this repo can be found in (sagebrush-xylem)[https://github.com/conservationtechlab/sagebrush-xylem].

The front-end repo with builds for dashboarding can be found here {sagebrush-canopy)[https://github.com/conservationtechlab/sagebrush-canopy].

# Station Versions
## LoRa Gateways
### Cellular
Cell enabled LoRa Gateway stations for remote deployments outside of the range of the nearest in-network Nanobeam. Not optimal, but often necessary. 
### NanoBeam
For deployments within range of a Nanobeam that's within network. Preferred.
## SageCam
### NanoBeam
SageCam set-ups within range of a Nanobeam within network.
#### V1 vs V2
The versioning associated with the SageCam Nanobeam builds does not affect usage or functionality. The jump from v1 to v2 simply reflects a reduction of the number of parts, and is slightly more cost effective.
### Wifi
SageCam setups without a Nanobeam for when the deployment location has access to a high bandwith, secure, and strong Wifi signal.
### Plug-In
SageCams on the network through Wifi AND/OR Nanobeam, but with a reliable AC power source, removes the need for solar panels, battery, and solar charge controller.
## SageMic
### Add-on
Any SageBRUSH system that has a Raspberry Pi can include a SageMic* with the addition of an additional hole and cable gland in the box, a microphone, a USB sound card adapter, and a cable from the sound card to the microphone. OR, just a cable and an audiomoth with a custom enclosure. 

*Cellular LoRa Gateway set-ups excluded due to networking limitations.
