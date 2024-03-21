# git-archive-program

Lists GitHub orgs and repositories that should be mirrored to https://git.ethquokkaops.io

## Puprose and goal

To archive and preserve the history of the Ethereum Network, archiving the code base for clients, dApps and other projects is important.
Also having another copy of the repositories might come in handy in the future.

## Contributing

To get an org or repository mirrored add them to the `mirror-sources.yaml`
Add the org name under the `orgs` key or the single repo under the `repo` key.

We encourage projects in the ecosystem to add their whole org. The `repo` feature is more tailored towards individuals.

Once added, please create a PR and once approved the mirror will be automatically picked up and will be active shortly after merging.
