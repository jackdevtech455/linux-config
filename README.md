# linux-config
Setup and configure a DevOps environment in linux

## Shell

FIsh - Friendly Interactive Shell

'''
fish install instructions
'''

## IDE

Neovim

'''
neovim install instructions
'''

## Window manager

tmux

'''
apt install tmux
'''

## SSH

Manage SSH keys

### Generate Key Pairs

'''
ssh-keygen -t ed25519 -C "jackdevtech455@gmail.com"
'''

### Check key Pairs

View Public key

'''
cat ~/.ssh/id_ed25519.pub
'''

View Private key

'''
cat ~/.ssh/id_ed25519
'''

### Add key to GitHub

1. Copy public SSH key: ```cat ~/.ssh/id_ed25519.pub```

1. Visit account at: https://github.com/jackdevtech455

2. Go to account settings: Profile (top right) > Settings

3. Go to keys page: Access (heading) > SSH and GPG keys

4. Create new SSH key: New SSH key

  1. Add title: 'Jack Ubuntu'

  2. Select Key Type: Authentication Key

  3. Paste copied public SSH key into 'Key'

    - It should look like this:

    '''
    ssh-ed25519
    AAAAC3NzaC1lZDI1NTE5AAAAIFHfzkUXRxl0f5i8fZauU+BVXm4J4kWhPLOhASiORpEs
    jack@jack-Latitude-5420
    '''
