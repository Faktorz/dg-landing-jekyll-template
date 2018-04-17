---
layout: page
title: FAQ
date: 2018-04-17 21:50:38 +0000
description: Frequently Asked Questions - The Digital Garage
---
# Product
### What happens when my online starter account is inactive?
We periodically remove inactive users from openshift online starter to free up resources for new users. If your account is removed, you can resubscribe at any time.

Openshift online starter is intended for learning and experimenting, not for hosting projects. Accordingly, we consider "Activity" to mean that you are using your account to build and deploy applications.

If you are using openshift online starter infrequently, we recommend that you backup your applications and data. See "Creating a template from existing objects" to backup your applications and "Backing up and restoring databases" to backup your databases.

### Can I run production services on openshift online?
Yes! The openshift online pro plan is intended for production services and hosting.

### Is my data safe and secure?
You bet. Red hat has a long history of managing the packages that make up red hat enterprise linux, including industry-leading responsiveness to security vulnerabilities and managing its online presence on linux systems. Red hat openshift online is managed and maintained by red hat as part of the service. Learn more.

### Can I create a multiple accounts on openshift online?
You may not (or permit third parties to) create multiple accounts or otherwise access the openshift online in a manner that is intended to avoid fees or to circumvent maximum capacity thresholds for the service. Learn more.

### What are the resource limits for the openshift online starter plan?
Each user can create 1 project with up to 4 services using 1 gib memory, 2 cpu cores, and a 1 gib persistent volumes. For more detailed limits, see the full plan comparison.

### What are terminating resources?
Terminating resources are pods with an active deadline. These pods usually include builds, deployers, and jobs.

### What languages and datastores are supported?
Openshift online 3 currently supports java (8), .Net core (1.0, 1.1, 2.0), node.Js (4, 6), php (5.5, 5.6, 7), python (2.7, 3.4, 3.5), ruby (2.2, 2.3, 2.4), and perl (5.20, 5.24). Jenkins (2.X) is also available for ci/cd. Tomcat (7, 8), with support for with java (7, 8, ee), is available via red hat jboss web server. Supported quickstart application templates are available for apache http server, cakephp, dancer, django, node.Js, and ruby on rails. View all.

### What database services are supported?
Openshift online 3 currently supports mariadb (10.1), mongodb (2.6, 3.2), mysql (5.6, 5.7), postgresql (9.4, 9.5), and redis (3.2). View all.

### Can users run images from docker hub or push their own images to the registry?
Yes, but with a few caveats. For security reasons, no images that run processes as root are allowed. Additionally, any dockerfile volume instruction must be mounted with either a persistent volume claim (pvc) or an emptydir at this time.

# Pricing
### Can I upgrade from the starter plan to the pro plan?
You can have both! The openshift online pro plan gives you access to resources in the pro us east (n. Virginia) cluster. You can continue to use your openshift online starter plan resources on the starter us east (n. Virginia) or starter us west (oregon) cluster for learning, experimenting, and development.

### How can I use pro resources in multiple regions?
You can use pro resources in multiple regions by purchasing resources and paying the base price in each region separately.

### What form of payments do you accept?
We currently accept visa and mastercard credit cards.

### What is the billing cycle?
The billing cycle is by calendar month, or in other words from the 1st to the last day of a particular month.

### Do you offer refunds?
No, we do not offer refunds at this time.

### What currencies do you accept?
United states residents are billed in usd, canadian residents are billed in cad, european union member state residents are billed in eur, and all others are billed in usd.

# Support
How can I receive support for the offering?
Openshift online pro plan users have access to complimentary red hat basic support. Support plans are not available for the free openshift online starter plan, however, there are a wide variety of community support options available, including stack overflow, irc, our community mailing list, and by reaching out to our community enablement team.

### How do I report security flaws?
Red hat's bugzilla instance can also be used to log security sensitive bug reports (product=openshift online, version=3.X, groups=security) by selecting the "Security sensitive bug" flag (automatically selected with the provided link).

### What should I do when I find a bug?
You can find a list of known and reported issues in red hat's bugzilla instance. If your issue isn't listed, you can log a new bug report" (product=openshift online, version=3.X).

### Why was my access to starter removed?
We want to make everyone's wait time to get access to openshift online starter as short as possible. Accordingly, we remove access for users with no active resources from time to time to make room for new users. Whenever you are ready to use openshift, you can subscribe at manage.Openshift.Com to get access to starter again.