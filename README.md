# CONTRA - Setup party

## Required packaged

### 1. Terminal 

**Windows**

`Putty`, `Ubuntu for Windows`, `Git for Windows`, `Cygiwn` or simillar.

Preffered `Git for Windows`:

[https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe](https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe)

**MacOS**

Install `homebrew`:\
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
```
brew cask install iTerm2
```

**Linux** 

Built-in is just fine.

### 2. GIT

**Windows**
`Git for Windows` provides GIT commands.

**MacOS**
```
brew install git
```

**Linux**

Depends on distro: 

__Ubuntu/Debian based:__

```
sudo apt install -y git
```

__Fedora:__

```
sudo dnf install -y git
```

__Centos/Red Hat:__

```
sudo yum install -y git
```

### 3. AWSCLI

**Windows**

[https://s3.amazonaws.com/aws-cli/AWSCLI64PY3.msi](https://s3.amazonaws.com/aws-cli/AWSCLI64PY3.msi)

**MacOS**
```
brew install awscli
```

**Linux**

Install PIP:

__Ubuntu/Debian based:__
```
sudo apt install -y python-pip
```

__Fedora:__
```
sudo dnf install -y python-pip
```

__Centos/Red Hat:__
```
sudo yum install -y python-pip
```

PIP package:
```
sudo pip install awscli
```

... or install package from distro repo:

__Ubuntu/Debian based:__
```
sudo apt install -y awscli
```

__Fedora:__
```
sudo dnf install -y awscli 
```

__Centos/Red Hat:__
```
sudo yum install -y awscli
```

AWS Configuration:

Type in terminal:
```
aws configure
```

And provide the credentials that you should receive on your e-mail.

### 3. Docker + kubernetes

**Windows**

__**Hyper-V has to be enabled!**__\
[https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)

[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

**MacOS** 

[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

**Linux**

Install snap:\
[https://docs.snapcraft.io/installing-snapd/6735](https://docs.snapcraft.io/installing-snapd/6735)

snap package:
```
sudo snap install microk8s --classic
```

### 4. VSCode, python, SQLLite3, R, nextflow

**Windows**

**MacOS**

**Linux**

### GitHub Account

Create an account on GitHub: 
[https://github.com/](https://github.com/)