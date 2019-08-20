~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Install RVM, Ruby, Rails
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

# install curl
~$ sudo apt-get install curl

# install 
~$ sudo apt-get install git git-core build-essential openssl libgdbm-dev libncurses5-dev automake libtool bison libffi-dev nodejs


# install rvm
~$ gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

~$ curl -sSL https://get.rvm.io | bash -s stable

# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# после установки RVM нужно закрыть текущее окно терминала и открыть новое
# и в новом окне выполнить следующую команду(установить зависимости):

~$ rvm requirements

~$ rvm install 2.6.3

~$ rvm use 2.6.3 --default

~$ gem update --system

~$ gem install rails

~$ gem install bundler










