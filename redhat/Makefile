# ex: set ts=8 noet:

name-your-poison:

install-services:
	cp statsd /etc/init.d/
	ln -s /etc/init.d/statsd /etc/rc.d/rc5.d/S99statsd
	cp graphite /etc/init.d/
	ln -s /etc/init.d/graphite /etc/rc.d/rc5.d/S99graphite

uninstall-services:
	$(RM) /etc/rc.d/rc5.d/S99statsd
	$(RM) /etc/rc.d/rc5.d/S99graphite
	$(RM) /etc/init.d/statsd
	$(RM) /etc/init.d/graphite

