# SUMMER SCHOOL - Setup party

## Required packaged

### 1. Terminal 

**Windows:**

`Putty`, `Ubuntu for Windows (WSL)`, `Git for Windows`, `Cygwin` or simillar.

Preffered `Git for Windows`:

[https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe](https://github.com/git-for-windows/git/releases/download/v2.20.1.windows.1/Git-2.20.1-64-bit.exe)

**MacOS:**

Install `homebrew`:
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew cask install iTerm2
```

**Linux:** 

Built-in is just fine.

### 2. GIT

**Windows:**
`Git for Windows` provides GIT commands.

**MacOS:**
```
brew install git
```

**Linux:**

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

### 3. Docker + Kubernetes

**Windows:**

__**Hyper-V has to be enabled!**__\
[https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v)

Registration required for downloading Docker Desktop.\
[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

**MacOS:** 

Registration required for downloading Docker Desktop.\
[https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

**Linux:**

Install docker:
```
curl -fsSL https://get.docker.com -o get-docker.sh && sh get-docker.sh
```

Install docker-compose:
```
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

Install snap (should be already installed on ubuntu):\
[https://docs.snapcraft.io/installing-snapd/6735](https://docs.snapcraft.io/installing-snapd/6735)

Install MicroK8s using snap:
```
sudo snap install microk8s --classic
```

### 4. VSCode

[https://code.visualstudio.com/](https://code.visualstudio.com/)

### 5. Python

**Windows:**
```
https://www.python.org/downloads/windows/
```

**MacOS:**
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

### 6. Java

**Windows:**

[https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

**MacOS:**
```
brew tap caskroom/versions
brew cask install java8
```

**Linux:**
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

### 7. NextFlow

**Windows:**

Docker image will be provided.

**MacOS / Linux:**

[https://www.nextflow.io/docs/latest/getstarted.html](https://www.nextflow.io/docs/latest/getstarted.html)

### 8. SQLLite3

**Windows:**

[https://sqlite.org/download.html](https://sqlite.org/download.html)

**MacOS:**
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

### 9. R

**Windows:**

[https://cran.r-project.org/bin/windows/base/](https://cran.r-project.org/bin/windows/base/)

**MacOS:**
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

### 10. RStudio

[https://www.rstudio.com/products/rstudio/download/#download](https://www.rstudio.com/products/rstudio/download/#download)

### 11. Google Account

Create an account on Google:
[https://support.google.com/accounts/answer/27441?hl=en](https://support.google.com/accounts/answer/27441?hl=en)
