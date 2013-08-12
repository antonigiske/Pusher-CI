Pusher PHP Library (CI version)
===================

This is a CodeIgniter version of the PHP library (https://github.com/pusher/pusher-node-server).
You can find full documentation on that project there.

How to use
----------

    $this->load->library('pusher');
    $this->pusher->trigger('channel', 'event', array('message' => 'Hello World'));


License
-------
Copyright 2010, Squeeks. Licensed under the MIT license: http://www.opensource.org/licenses/mit-license.php

