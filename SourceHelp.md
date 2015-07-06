## Introduction ##

Since the build and deployment process only happens if the software correctly passes all tests and checks the trunk must be in an always working condition.  For this reason, the source code will not be posted on this website, but will be available for project members on a branch basis.

## Subversion Strategy ##

Each developer will have a dedicated branch for making changes.  It will be the responsibiliy of the developer to maintain the branch by regularly merging out of trunk changes.  When a defect is submitted for review, the changes will be picked up by the development owner and merged into a staging branch where all tests will be run to verify no regressions in functionality.  Upon successful execution, the code will be merged to trunk and all of the deployment jobs will be started.

## Source Server ##

The subversion server is located at http://drakeserv.dyndns.org:9001/repository/stamp-imageparsing.  Access is required to view and edit the source.  Upon receiving access, you will be provided with a branch and given full read/write access to the branch.  Please avoid doing meaningless revisions/commits as this will only expand the source tree. (However I do encourage committing nightly or whenever a significant change has occured).

## Eclipse Project ##

Eclipse project files are currently included in the source distribution.  This may change depending on if it impacts installs and setup of others projects.