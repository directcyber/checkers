# checkers

Files to check the existence of a vulnerability / patch. 

Care is taken to ensure that the checks are as legal and non-intrusive as possible, as we do our best to not exploit nor modify the target host.

## Contributing

Pull requests welcome! Please ensure your checker does not:

- modify the target host (e.g. change usernames, passwords, webpages)
- in case the checker obtains sensitive information over the network, do not print out sensitive information to the output, nor save them to the filesystem.
- impair or deny availability of the target (e.g. DOS, shutdown, crash)

See our playbook's [legal concerns](https://github.com/directcyber/playbook#legal-concerns) section for more information about legality.

