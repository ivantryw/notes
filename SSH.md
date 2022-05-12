# SSH
## Adding multiple ssh keys to github
1. ssh-keygen -t ed25519 -C "email_address@website.com"
2. eval "$(ssh-agent -s)"
3. ssh-add _the-ssh-key-file-location_
4. create config file in ~/.ssh/
5. copy the public key "your-key.pub" and paste into username/settings/ssh and gpg
