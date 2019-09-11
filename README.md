# Code Quarkus release

Manage releases for Code Quarkus

## To promote a new version to production

1. Check that staging is working as expected: https://stage.code.quarkus.io
2. Create a PR with the Code Quarkus commit hash to promote to production:
  https://github.com/quarkusio/code.quarkus.io-release/blob/master/code-quarkus-services/code-quarkus.yaml#L2
3. Wait for CI and merge
4. Production will automatically be updated with the new version (~3mins)

## Infra (Restricted access)

Staging: https://console.app-sre-stage.openshift.com/console/project/code-quarkus-stage/overview
Production: https://console.app-sre.openshift.com/console/project/code-quarkus-production/overview

## CI/CD (Restricted access)

https://ci.ext.devshift.net/view/code-quarkus/

