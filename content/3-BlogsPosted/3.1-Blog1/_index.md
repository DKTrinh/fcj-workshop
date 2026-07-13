---
title: "Blog 1"
date: 2026-07-13
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

 

# SESSION POLICIES IN AMAZON EKS POD IDENTITY

Amazon EKS Pod Identity has recently added the session policies feature, allowing you to narrow IAM permissions flexibly and precisely for each pod without needing to create many separate IAM roles. This is an important step forward that helps apply the principle of least privilege more effectively in large-scale Kubernetes environments.

Key points to know:

* A session policy is an inline IAM policy specified when creating or updating a Pod Identity association.
* Effective permissions equal the intersection between the IAM role permissions and the session policy. In other words, the session policy can only narrow permissions, not expand them.
* It helps avoid over-permissioning when a single IAM role is reused for multiple workloads with different needs.
* It supports both same-account and cross-account scenarios through IAM role chaining.
* It significantly reduces the number of IAM roles that need to be managed, helping avoid IAM quota limits in large clusters.
* It can be configured easily through the AWS Management Console, AWS CLI, or AWS SDK when creating an association between a Kubernetes ServiceAccount and an IAM role.

This feature is especially useful when many applications run under the same IAM role but require different permission restrictions. For example, one pod might only read a specific S3 bucket while another can only call a small set of APIs.

...Image...

...Link...

...Guide...