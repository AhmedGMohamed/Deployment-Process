#CircleCI Pipeline
---
This Repository is monitored by CircleCi. Any time code is pushed/pulled from the main branch of this repository, the CircleCI pipeline is triggered.

##Pipeline Events
---
The following events are triggered in the same order as listed when a change is made to the repository.
- Docker Environment Setup
- Install Node.js
- Install AWS CLI
- Configure AWS Access Key and Region
- Setup EB CLI
- Install the Front-end Dependencies
- Install the Back-end Dependencies
- Build the Front-end
- Build the Back-end
- Deploy the Front-end to AWS S3 bucket
- Deploy the Back-end to AWS EB environment