# Demo_2024


### Generate New SSH Key
- Open Git Bash.
- Paste the text below, replacing the email used in the example with your GitHub email address.
```
ssh-keygen -t ed25519 -C "your_email@example.com"

```
- Copy the SSH public key to your clipboard.
```
clip < ~/.ssh/id_ed25519.pub

```