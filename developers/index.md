---
layout: main
title: "Developers: Hack on IzPack!"
---

<div class="page-header">
  <h1>
    Developers: Hack on IzPack!
    <small>We love bug fixes, improvements and new features!</small>
  </h1>
</div>

<div class="alert alert-success">
  <h3>IzPack is an opensource project that values meritocracy.</h3>
  <span>Code speaks louder than endless discussions!</span>
</div>

<div class="alert alert-error">
  <h3>Do not attach patches to JIRA issues.</h3>
  <span>Attach a link to a pull request on our GitHub repository instead!</span>
</div>

## Git at Codehaus <small>(for official developers)</small>

Our canonical repository is hosted at [The Codehaus](http://codehaus.org/). This repository makes reference and only approved developers may push to it, and subsequently perform releases.

* read-only access: `git://git.codehaus.org/izpack.git`
* developers access: `ssh://git@git.codehaus.org/izpack.git`
* GitWeb: [http://git.codehaus.org/gitweb.cgi?p=izpack.git](http://git.codehaus.org/gitweb.cgi?p=izpack.git)

## IzPack on GitHub <small>(lowering the barrier to collaboration)</small>

We have an [*izpack* organization on GitHub](http://github.com/izpack) where a Git repository is hosted:

* GitHub: [http://github.com/izpack/izpack](http://github.com/izpack/izpack)
* read-only access: 
* organization-member access: 

## How to collaborate on GitHub

This repository acts as a gatekeeper to the canonical repository at Codehaus, and contributions are expected to be performed using pull-requests.

To minimize bureaucracy overhead, we adopt the following soft rules.

### If you are an external contributor:

1. fork us on GitHub,
2. craft your contribution, preferably in a development branch, making self-contained an many small commits,
3. send us a pull request.

The barrier to entry is probably lower than you may expect, however keep in mind that :

1. a good contribution has a test,
2. a new feature needs to be documented [in our wiki](http://docs.codehaus.org/display/IZPACK/User+documentation) once an organization members validates your pull-request,
3. you are intended to respect the source code format of existing files.

### If you are a member of the GitHub organization:

1. do not push directly to the `master` branch or to a version branch,
2. you may push feature development branches at will, just give them an explicit name and/or a JIRA issue identifier,
3. send a pull-request from either your own fork or a feature branch,
4. a fellow organization member must approve the pull-request,
5. if nobody reacts to your pull request within 3 days then you can merge yourself,
6. when reviewing an external contribution, do not forget to ask the contributor to edit the wiki documentation if you approve it.

### If you are an IzPack developer on Codehaus:

1. please go through the GitHub repository instead of directly pushing to Codehaus,
2. you are free to push the state of the GitHub repository branches to Codehaus,
3. however, do not push feature development branches to Codehaus, only `master` and version branches.



