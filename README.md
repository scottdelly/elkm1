elkm1
=====

This is a perl API I found for interfacing with the ELK M1 home automation system

Original Notes Below:

NAME
    ElkM1::Control - a module allowing control of the ElkM1 Security / Home Automation system.

    ElkM1::Control is a set of modules which provide an API for communication and control with the 
    ElkM1 security and home automation system. This package contains no user-runnable code, but is 
    an API with which you can build applications that can communicate with the Elk. With this package
    you can command the panel to do anything you could do at the keypad. You can also recieve messages 
    when certain events occur on the panel such as a zone being violated, a task activating, etc. 

    This package requires the use of the Elk ethernet module. It is very possible that this could be 
    easily ported to use the serial port. I'd welcome patches to make this happen.

    This system can use either the secure port (2601) or the insecure port (2101). See the use_ssl
    option in the new method of ElkM1::Control.  

PREREQUISITES 

    This package requires IO::Socket::INET and IO::Socket::SSL modules.

HOW TO BUILD 

    This package should be a fairly straight forward build. 

    Perl Makefile.PL
    make
    make test

HOW TO INSTALL 

    make install

AUTHORS
    James Russo, "<jr@halo3.net>"

COPYRIGHT
    Copyright 2006 James Russo, All Rights Reserved.

    This program is free software; you can redistribute it and/or modify it
    under the same terms as Perl itself.
