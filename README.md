The Eclipse SDV Blueprints project is a collaborative initiative led by Eclipse SDV members to bring the software defined vehicle concepts to life.

The project hosts a collection of blueprints that demonstrate the application of technologies developed in the context of the Eclipse SDV Working Group.

This repository contains the digital.auto & AosEdge Blueprint which enables quick seamless prototyping with unified Mixed-Critical Deployment & Orchestration platforms for Virtual & HW environments.

## Blueprint overview

The following diagram provides a high level overview of how digital.auto (Eclipes autowrx) the cloud prototyping environment, AosEdge the mixed-critical deployment and orchestration platform, and other Eclipse Blueprints, Eclipse S-CORE and virtual/HW environments would interact.

[overview diagram]

## How it is done

Eclipse autowrx (playground.digital.auto) and AosEdge is already connected with a Service Connector. Once you create a prototype app or service in the playground that utilizes standardized vehicle API, the app/service's python model can be shared through the Service Connector to AosEdge. The Service Connector will repackage the model in format that enables AosCloud to handle. AosEdge can have your necessary environments registered as units, whether it may be virtual or physical hardware such as test board or even actual vehicle. User can deploy the repackaged model as a container which AosCore, the embedded runtime orchestrator, can orchestrate within the virtual or physical device. Within the whole development and deployment lifecycle of the model, there would be many other Eclipse Blueprints that can be utilized.

## Code

AosEdge repo

Service Connector repo

## Quick start

1. Sign up and setup playground.digital.auto
2. Sign up and setup AosEdge
3. ...
