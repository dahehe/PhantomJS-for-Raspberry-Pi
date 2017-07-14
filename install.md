# Installing PhantomJS on the Raspberry Pi

## 1.Go to home directory download PhantomJS
```
cd ~
git clone https://github.com/dahehe/PhantomJS-for-Raspberry-Pi.git
```

## 2.Apply permissions to run it
```
first:
chmod -x ~/PhantomJS-for-Raspberry-Pi/bin/phantomjs
then:
chmod 775 ~/PhantomJS-for-Raspberry-Pi/bin/phantomjs
```

## 3.Symlink it to bin directory.
```
sudo ln -s /home/pi/PhantomJS-for-Raspberry-Pi/bin/phantomjs /usr/bin/
```

Now you can use the 'phantomjs' command!
