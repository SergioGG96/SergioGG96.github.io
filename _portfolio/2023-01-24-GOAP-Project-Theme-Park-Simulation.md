---
layout: post
title: "GOAP Project: Theme Park Simulation."
subtitle: "Simulation of visitor's actions in a theme park using Goal-Oriented Action Planning (GOAP)."
date: 2023-01-24 00:00:00 -0400
background: '/img/portfolio/GOAP-Project-Theme-Park/themePark.PNG'
icon: '/gif/GOAP-Project-Theme-Park/FerrisWheel.gif'
---

# What is GOAP

GOAP is an AI system that will give your agents options and the tools to make intelligent decisions without having to maintain a large and complex finite state machine. 

For this project we have simulated a theme park where we have the park visitors, workers, janitors and mechanics.

<img src="/gif/GOAP-Project-Theme-Park/FerrisWheel.gif" alt="img" class="responsive-gif" width="256" height="256"/>

I will start by describing each agent and their actions around the park.

___

## Visitor

Visitors intend to have fun in the park, so they usually will want to ride the attractions several times before leaving.

Its actions will be:

- ENTRY: Reach the park by crossing the entry.
- QUEUE: Waiting in the queue to get a ticket for the attraction.
- RIDE: When the worker gives them the ticket they will get on the ride and once they finish they will queue up again.
- EXIT: When they get tired (they ride a certain number of times) they will leave the park.

<img src="/img/portfolio/GOAP-Project-Theme-Park/Visitor.png" alt="img" class="responsive-gif" width="128" height="128"/>

___

## Worker

The worker will wait for the queue of visitors to give them the ticket by approaching them.

Its actions will be:

- ATTEND: They will wait until there is a queue of visitors to attend to them.
- GIVE TICKET: He approaches the visitor to give them the ticket and they return to their place.
- REST: Sometimes they will feel tired and go to the staff area.

<img src="/img/portfolio/GOAP-Project-Theme-Park/Worker.png" alt="img" class="responsive-gif" width="128" height="128"/>

___

## Janitor

The janitors will clean up trash in the area as visitors will occasionally litter the area.

Its actions will be:
- CLEAN: When a visitor throws trash on the ground, the janitors will pick it up immediately.
- REST: As well as workers, sometimes they will feel tired and go to the staff area.

<img src="/img/portfolio/GOAP-Project-Theme-Park/Bedel.png" alt="img" class="responsive-gif" width="128" height="128"/>

___

## Mechanic

Each time a visitor rides an attraction, it will gradually break down. When the ride is broken, the mechanic will repair it.

Its actions will be:
- REPAIR: When an attraction crashes, the mechanic will repair it, and the next time it will crash with a random number of rides. Visitors will not be able to ride the attractions while the mechanic is repairing them (but will let those who were already on the rides finish riding)
- REST: As well as workers, sometimes they will feel tired and go to the staff area.

<img src="/img/portfolio/GOAP-Project-Theme-Park/Mechanic.png" alt="img" class="responsive-gif" width="128" height="128"/>

___

## Example GIF execution

<img src="/gif/GOAP-Project-Theme-Park/themeParkGOAP.gif" alt="img" class="responsive-img" width="800" height="600"/>