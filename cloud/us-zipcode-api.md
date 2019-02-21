# Changelog - [US ZIP Code API](https://smartystreets.com/docs/cloud/us-zipcode-api)

All notable changes to the US ZIP Code API will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## Unreleased

Changes:

- Overhauling module and deployment system. (No public-facing changes expected.)


## 4.0.0 - 2018-12-26

IMPROVEMENTS:

- ZIP Code inputs that consist only of zeros are now discarded as if they were blank, but only if supplied along with non-blank City and State input values.