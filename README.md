# Managing Secrets with Chef

## Abstract

Managing Secrets with Chef is a comprehensive instructor-led course exploring the process of managing and distributing secrets. throughout your infrastructure

Managing infrastructure requires the coordination of many different applications and actors. Enabling secure communication between applications and the actors requires that a number of systems to trust one another. This means the distribution of keys, passwords, and certificates. When managing your infrastructure it can be difficult to maintain and distribute these secrets in a secure way.

Participants will learn how to securely store and deliver secrets across nodes. At the end of the course, learners will have created a code repository that can reviewed and applied to solve the management of real business secrets.

## Webinar Abstract

Managing infrastructure requires the coordination of many different applications and actors. Enabling secure communication between applications and the actors requires that a number of systems to trust one another. This means the distribution of keys, passwords, and certificates. When managing your infrastructure it can be difficult to maintain and distribute these secrets in a secure way.

In this webinar the facilitator will explain why it is important to manage secrets and how Chef is able to manage secrets through tools like encrypted data bags and Chef Vault. When we're done you'll understand the importance of security through encryption (over obscurity), how to securely manage those secrets with Chef, and know where to continue to build these skills.

## Learner Requirements

The content assumes the leaners have:

* A workstation with ChefDK installed.
* A Chef Server
* Authenticated with that Chef Server
* A node bootstrapped named 'node1'
* A node that can be reached through `knife ssh`

The content assumes individuals understands:

* Using `knife`
* Using Search through `knife`
* Creating a Recipe
* Creating a Cookbook
* Using Search within a Recipe
* Using Resources

## Agenda

### Data Bags

> This content is objective complete and command complete.

This tutorial walks the learner through creating data bags to manage users and groups within their organization. The created users contain no sensitive information.

### Encrypted Data Bags

> NOT YET WRITTEN

With the new user accounts that were created there is no way to login as those users. We walk through adding public keys to the authorized keys list.

We want to add passwords for the following users. This cannot be done in plaintext. We introduce the learners to encrypted data bags. Generating a shared key, encrypting the data, and then delivering the key to the node where it is needed.

### Chef Vault

> NOT YET WRITTEN

Delivering the encrypted key to all the nodes and individuals that need to view this data is problematic. We need a way to have individual and node based access to that information. In this section we lead the learner through setting up chef-vault to better manage the secrets.

## Published Content

This material is CURRENTLY IN DEVELOPMENT.

## Known Issues

There are no known issues as this material is CURRENTLY IN DEVELOPMENT.

## Workstation Setup

This workstation setup requirements have not been created as this material is CURRENTLY IN DEVELOPMENT.
