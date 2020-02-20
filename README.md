# Code Quarkus release

Manage releases for Code Quarkus

## To promote a new version to production

1. Check that staging is working as expected: https://stage.code.quarkus.io
2. Create a PR with the Code Quarkus commit hash to promote to production:
  https://github.com/quarkusio/code.quarkus.io-release/blob/master/code-quarkus-services/code-quarkus.yaml#L2
3. Wait for CI and merge
4. Production will automatically be updated with the new version (~3mins)

## Infra Managed by Red Hat app-sre team 


All those links have restricted access:

- Staging: https://console-openshift-console.apps.app-sre-stage-0.k3s7.p1.openshiftapps.com/k8s/cluster/projects
- Production: https://console-openshift-console.apps.app-sre-prod-01.i7w5.p1.openshiftapps.com/k8s/cluster/projects/code-quarkus-production
- CI/CD: https://ci.ext.devshift.net/view/code-quarkus/
- Jira: https://issues.redhat.com//projects/APPSRE/issues/
- Infra repository: https://gitlab.cee.redhat.com/service/app-interface
- Sentry: https://sentry.devshift.net/
- Slack: https://coreos.slack.com (channel sd-app-sre)


To request access, please contact adamevin@redhat.com
