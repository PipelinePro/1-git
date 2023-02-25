# Solution

## Please don't read this file until you complete the project on your own.

Step 1: Generate an SSH key pair on John's local machine using the `ssh-keygen` command.

Step 2: Copy the public key to John's clipboard using the command `pbcopy < ~/.ssh/id_rsa.pub`.

Step 3: Add the public key to John's GitHub account by going to `Settings` -> `SSH and GPG keys` -> `New SSH key`, and pasting the public key into the text box.

Step 4: Test the connection by running the command `ssh -T git@github.com` on John's local machine. If successful, John will see a message that confirms the connection is established.

Step 5: Configure Git to use SSH by running the command `git config --global url."git@github.com:".insteadOf "https://github.com/"` on John's local machine.

Step 6: Clone the repository using `git clone` command.
