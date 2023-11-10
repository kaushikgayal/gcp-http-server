# gcp-http-server
Module to create Apache Server in GCP.
This module consists of 4 tests to test below scenarios:
1. Good Input validation
2. Bad Input validation
3. Validating the names of VM Instance
4. Intergation Testing - Testing whether the website is accessible from Internet or not?

Run below command to set required environment variable:
```bash
export TF_VAR_auth_token=$(gcloud auth print-access-token)
```
