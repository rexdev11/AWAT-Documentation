---
title: "Crawler"
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
    Collecting bool
    Processing bool
    StandingBy bool
    Errored bool
}

```

## Initialize

```go

type CrawlerSpec struct {
    ID string
    URLS []string
}

type DocumentObject struct {
	ID string
	Source string
	Elements []string
	Date int
}

type CrawlerResponse struct {
	Payload 
}

```
- SpecBuilder
    
    - `buildSpec()` => CrawlerSpec 
    - `setSpec()` => CrawlerSpec 

## Scrape

- Pattern Matching
    
    - `matchRegEx(pattern []string)` => CrawlerResponse
    - `matchString(pattern []string)` => CrawlerResponse

- Document 

## Retrieval

- Resources
    
    - `fetchDocument([]cssSelectoers)` => CrawlerResponse
    - `fetchWhole(url, pattern)` => CrawlerResponse  
    - `fetchCheckFile()` =>  CrawlerResponse

