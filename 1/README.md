# Setup passwordless authentication with Git

## Scenario

John has just started working at ABC Corp as a software developer. He has been tasked with setting up a passwordless authentication with GitHub from his local machine to access the organization's repositories. As John is new to the organization and unfamiliar with the process, he reaches out to you for guidance.

As a DevOps engineer, you are going to help John for setting up passwordless authentication.

You will explain that by setting up passwordless authentication with GitHub, John can easily access the organization's repositories without the need to repeatedly enter his login credentials. This saves time and reduces the risk of unauthorized access.

You will also remind John that it is important to keep his private key secure and not share it with anyone. If the private key is compromised, an attacker could gain access to John's GitHub account and the organization's repositories.

By following your guidance, John is able to successfully set up passwordless authentication with GitHub and access the organization's repositories from his local machine. He thanks you for her help and looks forward to using Git more efficiently in his work.

## What to do?

In order to help John, perform the below activity:

1. Create a new GitHub organization with any name.
1. Create a new repository with one empty `README.md` file with private access under the same organization.
1. You can create a new separate GitHub account for John and provide access to the organization you just created or you can use your own account as well.
1. Generate a new SSH keypair on your John's local machine.
1. Go to Github and upload public key with name `John Machine`.
1. Test the connection from John's machine without cloning any repository.
1. Configure git to use ssh by default on John's machine.
1. Clone the repository of organization.

## Acceptance criteria

John should be able to clone, commit and push to the repository without using any passwords.
