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

In order to generate your AWS keys:\
[https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#Using_CreateAccessKey)

then type in terminal: \
```
aws configure
```

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

### 4. VSCode

[https://code.visualstudio.com/](https://code.visualstudio.com/)

Install the `sftp` plugin:\
[https://code.visualstudio.com/docs/editor/extension-gallery](https://code.visualstudio.com/docs/editor/extension-gallery)

Configuration of `sftp` plugin:
```
{
    "name": "aws-server",
    "privateKeyPath": "~/.ssh/id_rsa",
    "username": "ubuntu",
    "host": "your-host-here",
    "protocol": "sftp",
    "port": 22,
    "remotePath": "/home/ubuntu/contra-nextflow",
    "uploadOnSave":true,
    "syncOption.delete":true
}
```
### 5. Python

**Windows**
```
https://www.python.org/downloads/windows/
```

**MacOS**
```
brew install python
```

**Linux**
__Ubuntu/Debian based:__
```
sudo apt install -y python-dev
```

__Fedora:__
```
sudo dnf install -y python-devel
```

__Centos/Red Hat:__
```
sudo yum install -y python python-devel
```

### 6. SQLLite3

**Windows**

[https://sqlite.org/download.html](https://sqlite.org/download.html)

**MacOS**
```
brew install sqlite
```

**Linux**

__Ubuntu/Debian based:__
```
sudo apt install -y sqlite3
```

__Fedora:__
```
sudo dnf install sqlite
```

__Centos/Red Hat:__
```
sudo yum install -y libsqlite3x-devel.x86_64
```

### 7. R

**Windows**

[https://cran.r-project.org/bin/windows/base/](https://cran.r-project.org/bin/windows/base/)

**MacOS**
```
brew install r
```

**Linux**
__Ubuntu/Debian based:__

[https://www.digitalocean.com/community/tutorials/how-to-install-r-on-ubuntu-18-04](https://www.digitalocean.com/community/tutorials/how-to-install-r-on-ubuntu-18-04)

__Fedora:__
```
sudo dnf install -y R
```

__Centos/Red Hat:__
```
sudo yum install -y R
```

### 8. Java

**Windows**

[https://cran.r-project.org/bin/windows/base/](https://cran.r-project.org/bin/windows/base/)

**MacOS**
```
brew tap caskroom/versions
brew cask install java8
```

**Linux**
__Ubuntu/Debian based:__
```
sudo apt install -y openjdk-8-jdk
```

__Fedora:__
```
dnf install java-1.8.0-openjdk
```

__Centos/Red Hat:__
```
sudo yum install java-1.8.0-openjdk-devel
```

### 9. NextFlow

**Windows**
Docker image will be provided.

**MacOS / Linux**

[https://www.nextflow.io/docs/latest/getstarted.html](https://www.nextflow.io/docs/latest/getstarted.html)


### 10. GitHub Account

Create an account on GitHub: 
[https://github.com/](https://github.com/)

### 11. Google Account

Create an account on Google:
[https://support.google.com/accounts/answer/27441?hl=en](https://support.google.com/accounts/answer/27441?hl=en)