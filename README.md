# 2017-cloud-workflows-misc

This repo contains some nascent tutorials and examples using
[the Common Workflow Language (CWL)](commonwl.org) to run workflows
at the command line.

## Using the CWL reference implementation

This is the canonical way to do things, matching the usage in documentation
provided by the CWL project and others.

#### Example: [Install and run a workflow with cwlref-runner](install-and-run-with-cwltool.md)

## Using the dockstore client

This is a full install of the [dockstore](https://dockstore.org/docs) client.

A few notes:

* a simplified version of what's in the dockstore docs :)
* Java is needed here!
* Uses the `dockstore`-specific extension of putting file names in the
  input object to specify remote input and output locations
* the Dockstore client can also be used for adding and editing entries on Dockstore as well as running WDL (https://github.com/broadinstitute/wdl) workflows   

#### Example: [Install and run dockstore](install-and-run-with-dockstore.md)
