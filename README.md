# **mkignore**

## What is it ?

A shell script for automatically create .gitignore file with specified configuration using [gitignore.io](www.gitignore.io)

## Prerequisites

```
sudo apt install git curl
```

## Installation

```
git clone <https-or-ssh-link-of-the-repo>
```

```
cd mkignore
```
```
chmod u+x ./mkignore
```
```
cp -r ./mkignore /usr/bin/
```
  
## How it works

create **.gitignore**
```
mkignore template1,template2
```

look for its output
```
more .gitignore
```

## Reference

[List of all the templates](https://github.com/toptal/gitignore)

[Source](https://github.com/toptal/gitignore.io) 
