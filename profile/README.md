# Social Site Initiative

One individual, one site, one cert. 

Social sites.

## What?

We intend to break the current model of how person to person
or person to organization communication is conducted on the
internet.

Instead sites should be social - talk to each other directly.

## Why?

We are unhappy with the concept of centralized person to person
or person to organization communication on the internet. We even
consider federated protocols to infringe too much on the individuals
ability to control access to their data and maintain integrity
of their communication with others.

## How?

Each individual or organization should have their own site. Each site
will talk to other sites via more-or-less well-defined protocols
consituting a network of social sites.

Sites are able to connect to each other in a manner similar to a
social network or a communication protocol. Communication between
individuals is conducted on a site-to-site basis.

```
Individual A -> Site A -> Site B -> Individual B
```

Individuals are never expected to connect to other individuals sites
directly to share information with that individual, instead they conduct
that communication through their own site which in turn communicates
with the other individuals site. This has several advantages:

* Sites need not maintain credentials for other individuals than the owner.
* Sites are able to validate the origin of communication from others via
  a challenge-response protocol.

## A deeper why

Hopefully this enables more open discourse on the internet and more
individual responsibility. By having communication originate from
an individuals site that individual is the editor and publisher of
their own opinions, there is no moderator nor anyone to blame.

* There are no algorithms, other than the ones someone chooses to
  run.
* There are no ads, other than the ones someones chooses to host.
* Individuals are traceable to their domain, which should be traceable
  to a DNS registrar.


## A deeper how

A number of steps are needed to achieve these goals:

1. Defition of communication protocols.
2. Writing of sofware to use these protocols.
   a) New software using these protocols.
   b) Plugins for existing software.

### Communication Protocols

The suggested initial protocols:

* s2sp - the site-2-site-protocol - intended for sites to connect
  and validate each other, also provide logins if needed.
* s2scp - the site-2-site-client-protocol - intended for the owner
  of an individual social site to communicate with their site and
  receive updates.
* s2sbp - the site-2-site-blog-protocol - intended to post blog
  entries, respond with comments and do micro-blogging.
