# Data Bags

This repository contains a number of exercises that lead the learner through using Data Bags. This content stands alone from any other content is meant to be taught as an additional module.

## Prerequisites

The content assumes the leaners have:

* A Chef Server
* Authenticated with the Chef Server
* A node bootstrapped named 'node1'
* A node that can be reached through `knife ssh`

The content assumes individuals understands:

* Using `knife`
* Using Search through `knife`
* Creating a Recipe
* Creating a Cookbook
* Using Search within a Recipe
* Using Resources

## Material

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
