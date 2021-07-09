# Grafana SolarNetwork Datasource

## Overview
This plugin adds a SolarNetwork datasource to Grafana. It has a backend
component in order to provide a signing key to the frontend without
revealing the secret.

## Build Requirements
As well as the normal npm dependencies, you will need Go 1.16+ and mage
installed and available on the path. These are for the backend component.

## Building

```
npm run build
```
This will build everything to the dist/ directory.
