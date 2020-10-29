# eggd_workflow_dx_checker
Workflow for running Sentieon + eggd_dx_checker

## What does this workflow do?
Runs Sentieon followed by [eggd_dx_checker][dx-checker-link].

## What are typical use cases for this workflow?
Used to check for effects of weekly DNAnexus changes to ensure functionality of Sentieon is unaffacted.

## What data are required for this app to run?
Inputs defined in workflow, includes both left and right FASTQs and a previously generated VCF from these FASTQs.

## What does this app output?
Standard outputs from Sentieon, a text file with any differences in the VCFs and a Slack notification.

### This was made by EMEE GLH

[dx-checker-link]: https://github.com/eastgenomics/eggd_dx_checker
