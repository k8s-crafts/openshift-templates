# OpenShift Templates

This is a list of convenient [Templates](https://docs.openshift.com/container-platform/4.16/openshift_images/using-templates.html) for use with OpenShift Container Platform.

## Background

A **Template** is a resource that describes a set of k8s/openshift objects that can be configured with parameters to be created on OpenShift. Note that RBAC applies here so you can only create objects that you have permissions to create. [See more](https://docs.openshift.com/container-platform/4.16/openshift_images/using-templates.html).

## List of templates

| Template | Description |
|:--------:|:-----------:|
| [pgAdmin](./pgadmin/)  | A simple deployment for a [pgAdmin](https://www.pgadmin.org/) instance to work with PostgreSQL |

## Contributing

Simply create the directory containing the template and add a new entry in the above table.
