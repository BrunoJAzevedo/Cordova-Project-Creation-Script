# Cordova-Project-Creation-Script

Tired of having to do several commands every time you want to create a cordova project? This script helps you automate this process.

## Suggested installation

If it does not exists create a _bin_ directory in your home directory (_~_)

```bash
cd ~
mkdir bin
```

---

### Bash

Add to _.bash_profile_ which will be located at _~/.bash_profile_. If does not exist create _.bash_profile_:

`export PATH=$PATH:/Users/{whoami}/bin`

### Zsh

Add to _.zshrc_:

`export PATH=$PATH:/Users/{whoami}/bin`

---

In _bin_ directory add the _cordova-create-project_ file. 
In the same bin directory make the _cordova-create-project_ an executable file: 

```bash
chmod u+x cordova-create-project
```

Now anywhere run `cordova-create-project` and follow the instructions

And Tadaa you have an easier way to create your cordova project
