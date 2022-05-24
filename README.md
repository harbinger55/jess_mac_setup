# Pre run commands:
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew install ansible

xcode-select --install
```

**Sign into the apple store**
# Running the playbook
checkout the repo and cd into it

```bash
git clone git@github.com:harbinger55/jess_mac_setup.git
cd mac_setup
```

Then run the anible playbook

```bash
ansible-playbook ./mac_setup.yml
```
