# Gitcamp #

Script that loads Basecamp todo lists into Git commit messages, and marks todos as complete if they are kept in the commit message.

# Install #
	
	# Install Zend Framework
	sudo pear channel-discover zend.googlecode.com/svn
	sudo pear install zend/zend
	
	# Install gitcamp
    git clone ssh://git@git.brainstormmedia.com/bsm/gitcamp.git ~/Sites/gitcamp;
    echo "export PATH=~/Sites/gitcamp:$PATH" >> ~/.bash_profile;
    # Now run "gitcamp init" in a git repo