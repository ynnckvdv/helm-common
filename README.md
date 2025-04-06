This is meant as a base for all apps and will be a dependancy for a deployment Helm Chart where changes can be specified that are not the default.

The values.yml will contain the defaults for all applications in the future deployment Helm Chart.

The defaults will always have an ApplicationSet, Deployment and Service. Other resources will be able to be enabled or disabled.