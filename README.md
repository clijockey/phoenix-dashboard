# Overview 

As a customer it can be extremely useful to have a dashboard showing the overall usage of your PCF deployments.

This is especially true when you have multiple-foundations and want to get a consolidated view of the world.

Based on initial interviews with customers that already have similar in-house tools/spreadsheets the following overall functionality has been highlighted (in no particular order); 

* Capacity
    * Allocated vs Consumed
* Org
    * Count
    * Name
    * Capacity
* Application Instances
    * Total
    * Running
* Apps
    * Buildpack (general grouping i.e. Java/Go etc.)
    * Memory
    * No of AIs
    * Disk
    * State
    * Create time
    * Update time
* Aggregate
    * Dev foundations
    * Prod foundations
* Per foundation
    * Tiles & Versions
    * Dev/Prod
    * URL OpsMgr
    * API
* Quota Definitions
* Buildpack Usage
    * Identify lack of migrations - app/LoB/org/space
* LoB/Team classification
* GUIDs are important to track (names change GUIDs are consistent)
* App Crash Report
* Metadata
    * Billing Codes
    * LoB
    * Org Creation Date
    * Org Owner + Contacts
    * Foundation Name/country etc.

## Goals
The goal of this work is to provide a way for customers to visualise data from foundations, in a single point,

 

## Anti-Goals
 * Not duplicate Healthwatch functionality (although might extract data from Healthwatch)
 * Not duplicate Metrics functionality
 * Duplicate any other existing Pivotal tool, if the functionality does not work as required then feedback to that team should be provided
 * Calling this a "single pane of glass"



# Yet to do

- [x] Basic MVP collection of data
- [ ] MVP Dashboard
    - [ ] Tidy up HTML/JS in MVP
- [ ] Track the project to help with prioritisation and collaboration
- [ ] pipeline the deployment of the app
- [ ] Testing
- [ ] SpringBoot app for collection of data
- [ ] Persistent storage of the data 
- [ ] PKS

