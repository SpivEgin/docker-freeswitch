Supported tags and respective Dockerfile links

- `latest` ([Dockerfile](https://github.com/kovalyshyn/docker-freeswitch/blob/master/Dockerfile))
- `vanilla` ([Dockerfile](https://github.com/kovalyshyn/docker-freeswitch/blob/vanilla/Dockerfile))

## FreeSWITCH

[FreeSWITCH](http://www.freeswitch.org/) docker image

- Current version is `1.6.10`

### Default FreeSWITCH image

To run default FreeSWITCH with vanilla config, default music on hold and english sound files, just type:

	docker run -d -t --name=FS --net="host" webitel/freeswitch-base:vanilla

### FreeSWITCH client
	
	docker run -i --rm --net="host" -t webitel/freeswitch-base:vanilla fs_cli


## Supported Docker versions

This image is officially supported on Docker version `1.12` and newest.

## User Feedback

### Issues
If you have any problems with or questions about this image, please contact us through a [Customer Portal](https://my.webitel.com/).
