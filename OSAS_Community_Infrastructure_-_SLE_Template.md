# Service Level Expectations

## Background

This page describes the service level expectations developers using the Fedora Atomic blades supported by OSAS Community Infrastructure (ComInfra) team can expect. It is roughly based on a service management document produced by Cornell University's IT department. You can find more information here.

Note that ComInfra and Fedora Infrastructure depend on service provided by various upstream providers of Internet connectivity, software development communities and hardware providers, and may be constrained by service at these levels.

Current and past service status updates are available at TBD.

## Definitions

* *Service Critical* - Service is not functioning at all/unusable.
* *Service Major* - Service is working, but with a major issue or slowdown.
* *Service Minor* - Service is working, bug or cosmetic issue is seen.
* *Target Response time* - target time from notification of issue to response from OSAS CommInfra team.
* *Target Resolution time* - target time to resolve issue

## Planned Maintenance

From time to time Planned Maintenance will be scheduled. Announcements of these will be to the announce or devel-announce or cloud-announce lists and will also have a issue opened in the issue tracker. During Planned Maintenance services listed may be unavailable. Status will be updated to reflect any in progress Planned Maintenace.

## Primary Services

Primary services are hosted in the fedoraproject.org or getfedora.org domains and subdomains there of.

These services are the most critical to the Fedora Project mission and have the highest expectation for uptime.

_TODO_: make table listing domain/service and SLEs

## Secondary Services

Secondary services are hosted in other domains like fedorainfracloud.org, cloud.fedoraproject.org, etc

These services are maintained as time permits and have a lower expectation of uptime.

_TODO_: make table listing domain/service and SLEs

## Community Services

Community Services are services run entirely by community volunteers. These services have differing SLEs, but are often less supported than the above services.

_TODO_: make table listing domain/service and SLEs

## Internal infrastructure Services

Infrastructure runs some services for their own needs internally. These services include collectd for stats gathering, nagios, log processing, etc. These services typically have a lower priority than the above services and will be handled at the discretion of the Infrastructure team.


