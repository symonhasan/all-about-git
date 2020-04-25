# All About Git

## Getting Started

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 

### Git Installation

Git can be simply installed from [Git-Scm](https://git-scm.com/downloads) for any operating system as it is available for Windows , Mac & Linux. Installation process is very simple. 

### Git Version Check

After sucessfully installing Git to your machine you can now check version by typing the following command in your Terminal or Git Bash
```
git --version
```
You may now see your installed Git version.
![git version check](snapshot/0.png)
<p align="center">*Fig 1 - outcome of `git --version` command*</p>

### Git Global Config

Now once you have sucessfully installed git now you need to set up some global configuration variable. Now these variables are important because if you working with other developers then they need to know who is making which changes and many other things. Now there are two important variable. One is `user.name` and another one is `user.email`. Of course there are lot more than these two but as we are getting started as beginner these two are enough for us.

- To set your username
```
git config --global user.name "<your name>" 
```
- To set your email
```
git config --global user.email "<your email>" 
```
- To list all your configuration
```
git config --list
```

** Snapshots are given below **

![git global config](snapshot/2.png)
<p align="center">*Fig 2 - setting config variable*</p>
![git global config list](snapshot/3.png)
<p align="center">*Fig 3 - outcome of `git config --list` command*</p>

### Need Help?

If you need help regading any keyword you can try any of these two command
```
git help <keyword>
```
<p align="center">or</p>

```
git <keyword> --help
```

** Snapshots **
![git global config](snapshot/2_0.png)
<p align="center">*Fig 4 - fetching help for config keyword*</p>

![git global config list](snapshot/2_1.png)
<p align="center">*Fig 5 - outcome of `git config --help` command*</p>
