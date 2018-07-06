---
title : "Abraham Watson an Overview"
contributors : ["Rex iamrexdev@gmail.com"]
description : "A reference and high level abstraction of the entire system."
createdon : 20180702
---

# The OfGeist Project

*Synopsis* - An Open Source project for public empowerment. The project's purpose is to give each person's voice an 
equal and unrestrained impact in the decisions that create their civic policies. The mission is to bring effective 
solutions and support palatable visualized data to the public and provide public API's for sharing the data it finds.
Our hope is that providing the heavy lifting tasks in data mining will allow us to output publicly consumable information 
on all topics that affect their concerns. The ability for us to scale or information processing would allow us to invite 
any expert from any feild to contribute in ways that would give us in in every industry to contribute or critically analyze the way we implement , we cna bring the understanding insights to many aspects of the political environment, making the vast plane of information
easier to navigate and understand to every human it affects by allowing these tools to leverage in a transparent way, 
political and economic big data.  
 
# Abraham Watson (A-Wat)

*A-Wat* is a **Political Prediction Assistant** or could be considered a synthetic politician. It would give people the 
tooling need to gain on political big data and pathways to find data on topics of issues and and education on topics and information that is aimed to offer visualized understandings based of the sentiments of constituents difficult econ Modular analytical machine that maintains itself. 

# System Overview

A [GoLang](https://golang.io) based modular IA with web facing UI's.

# Module [ Entity Tax Projector, Discovery Project ]

A UI that allows users to simulate future values for their entities.  

# Deployment

**Dependencies**

Install `Hugo CLI`

Mac OS with Homebrew

```bash

brew install hugo

```

**Fetch source code and theme.**

```bash

git clone https://github.com/rexdev11/AWAT-Documentation.git
cd AWAT-Documentation
git submodule add https://github.com/jeblister/kube.git themes/kube

```

**Run on dev server**

```bash
hugo server --disableFastRender
```

**Build**

```bash
hugo
```

## APIs

- [History Integrity](/apis/integrity-control) - A chain of history that is stored on a SWARM IA to help ensure that files can only be appended to.
- [Triage](apis/triage) - Listens for heartbeats and on system and performs repairs. 
- [ErrorControl](apis/error-control) - Error recovery and handling. 

### Services

- [Server](apis/server) - Iris
- [Users](apis/users) - User
- [Entities](apis/entities) - An object that represents an undefined object that can spend money.
- [Admin](apis/admin) - Module Administration
- [Store](apis/store) - A place for persistence
- [Reflector](apis/reflector) - Examines live self and can perform operations and provide values for self conditionals. 
- [Crawler](apis/admin) - Automated document retrieval and refresher.
- [Algorithm](apis/builder) - learned process are assembled to provide serial operations for projections.
- [Time Travel / Prediction](apis/time-travel) - Manages the state of objects to display past and present values.
- [Alerts](apis/alerts) 

### Tests

- [TestBed](test/test) - Go Test 
- [Smoke](test/smoke) - Selenium
- [Unit](test/unit) - Go Test

### UX Flow

- Landing -> Login -> Dash -> Entity selected / set settings -> choose Time-Line point -> project / change Time-Line to change projections -> logout

### User Interfaces

- Login / User Settings
- Report / Result Modal 

# How to Contribute

## Content Standards

## Code Standards
