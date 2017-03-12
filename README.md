# An attempt to create a sample blog application using ROR

# Getting Started

##1. Dependencies:

    sudo apt-get install git-core curl zlib1g-dev build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev nodejs


	sudo apt-get install mysql-server mysql-client libmysqlclient-dev

##2. Ruby 2.3.1

	git clone https://github.com/rbenv/rbenv.git ~/.rbenv

	exec $SHELL

	git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build

	echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc

	exec $SHELL

	rbenv install 2.3.1

	rbenv global 2.3.1

	ruby -v

##3. Rails 4.2.7.1

	gem install bundler

	curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -

	sudo apt-get install -y nodejs

	gem install rails -v 4.2.7.1

	rbenv rehash

	rails -v


## Running Blog Application

	cd blog

	rails server

	
## URL Path

	localhost:3000/articles
