# Zhejiang University Open Source Software Mirrors

## Introdution

Scripts used in http://mirrors.zju.edu.cn .

These scripts are forked from Tsinghua University Network 
Administrators ( http://git.tuna.tsinghua.edu.cn/ ), originally 
used in [Tsinghua Open Source Software Mirror Sites](http://mirrors.tuna.tsinghua.edu.cn).

Great thanks to their brilliant work!

## License

The ftpsync scripts are derived from Debian ftpsync project, 
thus licensed under GPLv2. Other scripts with no license headers 
are all free softwares as well, waiting for the owners to choose 
specific licenses.

## Structure

	+- bin
	|  |
	|  +-- ftpsync		(modified from Debian)
	|  |
	|  +-- runmirrors	(modified from Debian, used to push notifications to downstream)
	|  |
	|  +-- simplersync	(simple rsync scripts for other repos, derived from ftpsync)
	|  |
	|  +-- updatecron	(simple scripts to update crontab)
	|
	+- etc
	|  |
	|  +-- global.conf	(global config file)
	|  |
	|  +-- REPO.conf	(per repo config file)
	|  |
	|  +-- crontab		(crontab)

## Current Status

### ftpsync

Derived from Debian project. Removed pushpdo, websync, typicalsync and some other unused scripts.

__runmirrors__ has not been tested! Push function might be broken!

### simplersync

Simple rsync scripts written by myself, used in non-Debian repos.

