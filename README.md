# Cloud Functions input plugin for Embulk

embulk file input plugin. 

- embulk : http://www.embulk.org/docs/

- embulk plugins : http://www.embulk.org/plugins/

Execute a function (Cloud Functions) in your GCP account and read the result data

## Overview

* **Plugin type**: file input
* **Resume supported**: no
* **Cleanup supported**: yes

## Detail

WIP

## Usage

### Install plugin

```bash
embulk gem install embulk-input-cloud_functions
```

## Configuration

WIP

- **project**: Google Cloud Platform (gcp) project id (string, required)
- **json_keyfile**: gcp service account's private key with json (string, required)

## Example

WIP

```yaml
in:
  type: cloud_functions
  project: googlecloudplatformproject
  json_keyfile: gcp-service-account-private-key.json
  parser:
    type: json
out: 
  type: stdout
```
