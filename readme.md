
# Requirements
> ** x-code command line tools **
> > to install xcode clt run the following command in your terminal
```
xcode-select --install
```
> ** npm **
> > if you do not have npm the easiest way to get it (if you are on mac) will be through homebrew
> > if you are running linux, try ``apt-get install node``` or ``` yum install node ```
> > to install homebrew copy the following command into your terminal
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
> > then you will want to run ```brew install node```
> > this command installs both node and npm
> ** git **
> > you will need git installed so you can clone this repository down
> > run ``` brew install git``` like wise use the same commands for linux
> > finally clone the repo down

> **gulp**
> > cd into the repo and run ```npm install gulp gulp-cli -g```

> **bower**
> > ``` npm install bower -g```

# Ready to really get going

## 1 => run npm install inside of the root directory of the repo.
## 2 =>  if you dont have gulp run npm install -g gulp-cli
## 3 => if you dont have bower run npm install -g bower-cli
## 4 => run gulp run this should build everythign by default but just in case heres the break down

## gulp build:all
gulp pack:all
gulp -T

finally just run gulp in terminal inside of the td directory
