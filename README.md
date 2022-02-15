# Runner Post Cleanup
A Github Action to clean the runner workspace - mostly copied from https://github.com/colpal/actions-clean. 

This runs a cleanup script as a post job action - just add the step anywhere in the job.

## Usage
```yaml
# ...
steps:
  - uses: TooMuch4U/runner-post-cleanup@v1
# - step 1
# - step 2
# - step 3
# - ...
```