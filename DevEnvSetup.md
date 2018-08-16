# Development Environment Setup

## Installation

### Operating System

#### Mac

##### Python 3

Execute the following commands one after the other

```bash
brew install pyenv
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile
source ~/.bash_profile
pyenv install 3.7.0
pyenv local 3.7.0
pyenv rehash
```

##### PostgreSQL

* Download and install from [https://postgresapp.com/](https://postgresapp.com/)
* Start the app and click `Initialize` button
* Then in the database shown, click on the one with name 'postgres'
* After that follow the instructions in `README.md` file to setup the database

#### Linux

...

#### Windows

...