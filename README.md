php-redis-migrate-sessions
==========================

Migrate PHP sessions from disk to redis using mass insertion protocol

Usage
=====

Download the file, change the php_session_dir and php_session_prefix vars.<br/>
Run the script and wait for it to finish, it takes 16min for 120K files on my
slowest system :-D<br/>
Usually the script needs to be run with a user with access to php session, that
are usually protected for security reasons.<br/>
The script also assumes redis is running and no credentials are necessary, if
this is not the case for you just change the script.
