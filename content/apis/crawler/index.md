---
title: "Crawler"
author: "Fred Grey (revenant.003@aol.com)"
description: "The crawler can retrieve any resource with a URL and match string patterns on the document."
weight: 100
---

# Crawler
A general purpose crawler that works asynchronously to retrieve data and documents from hosted resources. 

GO Objects

```go

type Pattern struct {
    Pattern string
    PatternType string
}

type Crawler interface {
    Id string
    Spec CrawlerSpec
    Patterns map[string] Pattern
}

type CrawlerStatus interface {
    collecting bool
    processing bool
    standingBy bool
    Errored bool
}

```

## Initialize

```go

type CrawlerSpec struct {
    Id string
    Urls []string
}

````

- SpecBuilder
    - `buildSpec()` => CrawlerResponse 

## Scrape

- Pattern Matching
    - `matchRegEx(pattern []string)` => CrawlerResponse
    - `matchString(pattern []string)` => CrawlerResponse

- Document 
    - `fetchDocument([]cssSelectoers)` => CrawlerResponse
    
## Retrieval

- Resource
    - `fetchAllOf(url, pattern)` => CrawlerResponse  
    - `fetchCheckFile` 

/**

**/


# System Overview

*Synopsis*  - An opensource project for public empowerment. The synthetic politician would give people tooling and pathways to education on topics and information that is aimed to offer visualized understandings based of the sentiments of constituents  difficult econ Modular analytical machine that maintains itself 

## User Interfaces

### Tax Code Projector
- User Panel / Entity Configuration

## Automated Programmatic Interfaces
- Crawler - automated document retrieval and refresher
- 

## Homeostasis (MetaCode)

# Deployment

- fetch / clone
- build
- code style / contribution standard
- pull requests 

# Module - Entity Tax Projections

- 

## Main Components

- (Summary)['#Summary']
- Base / Boiler
- Crawler
- Document Discovery
- Stores
- Algorithm Builder
- Managers
- Meta ( Reflection, Healing, Error Recovery and Homeostasis )

## Tests

- TestBed
- Smoke
- Unit

## UX Flow

Landing -> login -> dash -> entity selected / set settings -> choose timeline point -> project / change timeline to change projections -> logout

## 