# 20427-jquery

Demonstrates a jquery vulnerability fix PR that misses [GHSA-gxr4-xjj5-5px2](https://osv.dev/vulnerability/GHSA-gxr4-xjj5-5px2) due to a non-semver compliant version in OSV events:
```
DEBUG: Vulnerability GHSA-rmxg-73gg-4p98 affects jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Setting allowed version 3.0.0 to fix vulnerability GHSA-rmxg-73gg-4p98 in jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Vulnerability GHSA-jpcq-cgw6-v4j6 affects jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Setting allowed version 3.5.0 to fix vulnerability GHSA-jpcq-cgw6-v4j6 in jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Vulnerability GHSA-6c3j-c64m-qhgq affects jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Setting allowed version 3.4.0 to fix vulnerability GHSA-6c3j-c64m-qhgq in jquery 2.2.4 (repository=renovate-demo/20427-jquery)
DEBUG: Skipping OSV event with invalid version (repository=renovate-demo/20427-jquery)
       "event": {"introduced": "1.2"}
```
