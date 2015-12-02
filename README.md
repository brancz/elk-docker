ELK Docker
==========

Run the latest versions of the ELK stack within docker and log json formatted
logs to it.

	docker run --rm --log-driver=syslog --log-opt syslog-address=udp://localhost:5140 alpine cat '{"test":1}'
