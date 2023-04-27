# CircleCI

## Table of Contents

- [Usage](#usage)

### Usage

1. This project needs to following CircleCI Environment Variables:

```
AWS_REGION = XXX

AWS_ACCESS_KEY_ID_DEV = XXX
AWS_ACCESS_KEY_ID_STAGE = XXX
AWS_ACCESS_KEY_ID_PROD = XXX
AWS_SECRET_ACCESS_KEY_DEV = XXX
AWS_SECRET_ACCESS_KEY_STAGE = XXX
AWS_SECRET_ACCESS_KEY_PROD = XXX
AWS_SESSION_TOKEN = XXX

S3_ORIGIN_DEV = XXX
S3_ORIGIN_STAGE = XXX
S3_ORIGIN_PROD = XXX

// for auto tagging
GITHUB_PROJECT = https://github.com/xxx/xxxxx
