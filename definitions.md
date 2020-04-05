Firstly, I believe it is important to define what a "CLI application" is.

I believe that once we erode all semantics, at the base level all CLI applications can be defined with just two categories;

a. (subordinate) Relies on an API not native to the CLI binary
b. (superior) Relies on it's internal API only

For easy reference, I've simplified the definitions into "subordinate" and "superior" application types.

To provide more explanation, a subordinate application is a supplemental program that will compliment its superior, which would be the persistent service or process it relies on for a successful execution, whereas a superior application provides it's own API with which it interacts to complete commands.

Examples (off the top of my head) of some subordinate CLI applications;

- Vault
- Docker

Examples (off the top of my head) of some superior CLI applications;

- Coreutils
- Ansible?
- cURL
