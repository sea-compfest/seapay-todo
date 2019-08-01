# Things To Do Before Running Seapay

## Windows 10

### Install Postgresql 11.4
[link](https://www.datacamp.com/community/tutorials/installing-postgresql-windows-macosx)

### Install Java
Make sure you already have Java installed by using this command in command prompt
```
java -version
```
If java is not installed yet, install it
[link](https://carakode.com/cara-install-java-di-windows-10-64-bit/)

### Other tools
#### Postman
[link](https://www.getpostman.com/downloads/)

---

## Linux (Ubuntu)

### Install Postgresql
[link](https://tecadmin.net/install-postgresql-server-on-ubuntu/)

### Install Java
[link](https://tecadmin.net/install-oracle-java-8-ubuntu-via-ppa/)

### Install Postman
[link](https://www.getpostman.com/downloads/)

---

## OSX

### Install homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Postgresql

#### Install postgresql
```
brew install postgresql
```

#### Run (make sure it is running)
```
brew services restart postgresql
```

#### Verify installed postgres
```
psql -U postgres -c 'SELECT version();'
```

### Java
#### Install Java
```
brew cask install java
```

### Other tools
#### Postman
```
brew cask install postman
```
