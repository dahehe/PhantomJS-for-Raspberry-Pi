Installing PhantomJS on the Raspberry Pi

First make sure you are in your home directory.

cd ~
then...

git clone https://github.com/dahehe/PhantomJS-for-Raspberry-Pi.git
It's a big binary. She'll be busy for a bit.

Now we'll want to apply permissions to run it

chmod -x ~/PhantomJS-for-Raspberry-Pi/bin/phantomjs
also...

chmod 775 ~/PhantomJS-for-Raspberry-Pi/bin/phantomjs
Now symlink it your bin directory.

sudo ln -s /home/pi/PhantomJS-for-Raspberry-Pi/bin/phantomjs /usr/bin/
Now you can use the 'phantomjs' command!
