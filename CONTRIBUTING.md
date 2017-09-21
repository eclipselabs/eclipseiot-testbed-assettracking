# How to Contribute to this Open IoT Testbed

First of all, thanks for considering to contribute to the testbed. We really appreciate the time and effort you want to
spend helping to improve things around here. And help we can use :-)

Here is a (non-exclusive, non-prioritized) list of things you might be able to help us with:

* bug reports
* bug fixes
* improvements regarding code quality e.g. improving readability, performance, modularity etc.
* documentation (Getting Started guide, Examples, …)
* features (both ideas and code are welcome)
* tests

In order to get you started as fast as possible we need to go through some organizational issues first.

## Legal Requirements

This Open IoT Testbed is an initiative of the [Eclipse IoT](http://iot.eclipse.org) Working Group, hosted on EclipseLabs.
While it is not an "official" Eclipse project, we still put a lot of value in conforming to open source best practices, and making sure that the testbeds can be consumed and used easily by anyone interested. 
Therefore, we are doing our best to track the intellectual property for all the contributions made to the testbeds' code.

### File Headers
A proper header must be in place for any file contributed to the testbed. For a new contribution, please add the below header:

```
/*******************************************************************************
 * Copyright (c) <year> <legal entity> and others
 *
 * All rights reserved. This program and the accompanying materials
 * are made available under the terms of the Eclipse Public License v1.0
 * which accompanies this distribution, and is available at
 * http://www.eclipse.org/legal/epl-v10.html
 *
 *******************************************************************************/
 ```

 Please ensure \<year\> is replaced with the current year or range (e.g. 2017 or 2015, 2017).
 Please ensure \<legal entity\> is replaced with the relevant information. If you are editing an existing contribution, feel free
 to create or add your legal entity to the contributors section as such:

 ```
 /*******************************************************************************
 * Copyright (c) <year> <legal entity> and others
 *
 * All rights reserved. This program and the accompanying materials
 * are made available under the terms of the Eclipse Public License v1.0
 * which accompanies this distribution, and is available at
 * http://www.eclipse.org/legal/epl-v10.html
 *
 * Contributors:
 *     <legal entity>
 *******************************************************************************/
 ```

### Developer Certificate of Origin

We kindly ask that you comply with the commitments described in "Developer's Certificate of Origin 1.1", quoted at https://www.eclipse.org/legal/ECA.php.
See the "Submitting the Changes" section below for more details on how this works in practice.

## How to Contribute
The easiest way to contribute code/patches/whatever is by creating a GitHub pull request (PR). 

### Making your Changes

* Fork the repository on GitHub
* Create a new branch for your changes
* Make your changes
* Make sure copyright headers are included in (all) files including updated year(s)
* Make sure proper headers are in place for each file (see above Legal Requirements)
* Commit your changes into that branch
* Use descriptive and meaningful commit messages
* If you have a lot of commits squash them into a single commit
* Make sure you use the `-s` flag when committing as explained above
* Push your changes to your branch in your forked repository

### Submitting the Changes

Submit a pull request via the normal GitHub UI. Please include in the description of your pull request a verbatim copy of the following paragraphs of the "Developer's Certificate of Origin 1.1". 

```
By making a contribution to this project, I certify that:

The contribution was created in whole or in part by me and I have the right to submit it under the open source license indicated in the file or
The contribution is based upon previous work that, to the best of my knowledge, is covered under an appropriate open source license and I have the right under that license to submit that work with modifications, whether created in whole or in part by me, under the same open source license (unless I am permitted to submit under a different license), as indicated in the file or
The contribution was provided directly to me by some other person who certified (a), (b) or (c) and I have not modified it.
I understand and agree that this project and the contribution are public and that a record of the contribution (including all personal information I submit with it, including my signoff) is maintained indefinitely and may be redistributed consistent with this project or the open source license(s) involved.
```

### After Submitting

* Do not use your branch for any other development, otherwise further changes that you make will be visible in the PR.

## Becoming a Committer

If your company is officially a participant in the testbed, you may request committer rights so that you can apply changes to the repository directly. 

In order to initially gain committer rights, the rule of thumb is to first make some contributions to the testbed, by means of pull requests, to show that you deserve the status. Once a handful of your contributions have been accepted, you can ask to be added as a contributor on the GitHub repository by creating an issue - or maybe another committer will just add you without you even asking :)
