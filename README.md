Gitlab with chef and vagrant
----------------------------

This README is not yet complete, it represents work in progress (the final state of the Code and Cake by SoCraMOB in Münster on the 31st of Aug 2012.

Prerequisites:
* a prepackaged vagrant box (i.e. lucid32-with-ruby1.9.box)
* VirtualBox
* a recent ruby release (i.e. ruby1.9.3)

You'll have to install bundler which supplies `bundle`:
    $ sudo gem install bundler
    $ bundle -v
    Bundler version 1.2.0

Install all required gems:
    $ bundle install

Launch virtual machine using `vagrant`:
    $ vagrant up
    # lots of output…

Check, if vagrant launched the virtual machine correctly, by ssh-ing onto the guest:
    $ vagrant ssh

Alternatively, use `vagrant status`.
