# fuse-online-install-auto


## Installation

This fuse_online_config_variables.sh is used when the properties need to be dynamically passed in the the release.sh process. 
The jenkins job [1] has the variables configured to be substituted into the file at run time.  This file is copied to replace
an existing fuse_online_config.sh file so that release.sh will just pick up the variables at runtime.

[1]  https://fusesource-jenkins.rhev-ci-vms.eng.rdu2.redhat.com/view/JBoss%20Fuse%207.0/job/fuse-online-rollout/
