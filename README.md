# compliance-ordering-example

This is an example of using the [policy generator](https://github.com/stolostron/policy-generator-plugin) 
to create ACM policies that are ordered via dependencies.

At a glance, the main configuration is in [./policyGenerator.yaml](./policyGenerator.yaml), 
and the generated YAML is in [./out.yaml](./out.yaml), so you don't need to run
it yourself.

In addition, there is a hand-built policy to demonstrate how a policy might be
activated when another policy is NonCompliant:
[./example-certificate-remediation.yaml](./example-certificate-remediation.yaml)
