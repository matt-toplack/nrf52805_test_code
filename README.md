# nrf52805_test_code

## Background

Since I am using the nRF52805, I am using the nRF5 SDK. While I theoretically could use nRF Connect, the plans I have for the nRF52805 chips do not require an RTOS and I would likely have very little remaining flash available for my code. The main downsides to using the nRF5 SDK are: 

1. nRF SDK is in Maintenance Mode, so while security and bug fixes will continue, new features will not become available 

2. While there is documentation available, there is as much in the way of "getting started" documentation readily available (at least not that explained it in a way that someone unfamiliar to the nRF ecosystem or newer to bare metal embedded devices in general) nor does there appear to be much in the way of enthusiast material or tutorials. 

I intend to use this repo as my version of a step by step guide that will allow anyone with a basic grasp of embedded programming to bring up an nRF52 device using the nRF5 SDK. In my opinion, one of the biggest learning curves for a new embedded engineer is the switch from using something like the Arduino Framework, (which in general abstracts much of the lower level operations from the user and has a vast community of makers, tutorials and support) to a manufacturer's SDK. 

## Environment Setup

VS Code 1.96.0

nRF5 SDK

GNU Compiler (GCC) from GNU ARM Embedded Toolchain

nRF52805 Development Board (I will be using my custom board, see https://github.com/matt-toplack/fanstel_bc805m_based_nrf52805_development_board for more details)

## Getting Started