---
layout: page
title: census-geocoding-mcp
description: MCP server exposing the U.S. Census Bureau Geocoding API to AI assistants
importance: 1
category: software
---

[census-geocoding-mcp](https://github.com/hesscl/census-geocoding-mcp) is a Model Context Protocol (MCP) server written in JavaScript that gives AI assistants direct access to the U.S. Census Bureau's Geocoding Services API.

**Features:**
- Geocode single addresses (one-line or parsed) to coordinates and geographic identifiers
- Batch geocode up to 10,000 addresses at once
- Reverse geocode coordinates to Census geographies
- Look up FIPS codes for states, counties, tracts, and blocks
- Support for Puerto Rico addresses

**Use cases:** Attaching Census geographies to address data, generating FIPS codes for spatial joins, building location-aware research pipelines with LLM tools.
