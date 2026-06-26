# Project Name

## Overview
The headtracker tracks the 3d position of user's head in order for it to be used as computer input.

## Features
- Battery over-discharge protection circuit
- Built-in battery holder

## Hardware
It uses 3 SFH485P ir led's; an LM324 op-amp; a modified PS3 eye camera and a 3d printed chassis.

## Software
In order to calculate the 3d position and send the data over to computer programs we use opentrack which is an open-source software built for this purpose.

## Design Decisions
SFH485P led's were chosen due to their lower power, 1.5V forward voltage led's which maintain good enough light intesity levels to stand out over background IR reflections.
The LM324 op-amp was chosing due to its low cost and fitting design characteristics.
The chassis was 3d printed as it allows for great design flexibility while being durable, light and low cost.
