# Default Pint configuration

This repo contains our default pint configuration and is used by our projects.

## Requirements
* PHP ^8.1
* Pint ^10.10.6

## Installation

* [Install Pint](https://laravel.com/docs/10.x/pint#installation) 

Add the following script to your composer file:

```json
{
  "pint": [
    "@php vendor/bin/pint --config https://raw.githubusercontent.com/DIJ-digital/pint-config/main/pint.json"
  ]
}
```
