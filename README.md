weinre-practice
===============


## weinre是cordova的子项目 = (Web Inspector Remote)

weinre是cordova的子项目 see https://github.com/apache/cordova-weinre


官方文档

http://people.apache.org/~pmuellr/weinre/


Check out the latest docs: they explain everything:

http://people.apache.org/~pmuellr/weinre/docs/latest/
Install a recent version via npm:

https://www.npmjs.com/package/weinre

	➜  weinre-practice git:(master) sudo npm -g install weinre
	➜  weinre-practice git:(master) weinre -h
	usage:   weinre [options]
	version: 2.0.0-pre-I0Z7U9OV

	options:
	    --httpPort     port to run the http server on        default: 8080
	    --boundHost    ip address to bind the server to      default: localhost
	    --verbose      print more diagnostics                default: false
	    --debug        print even more diagnostics           default: false
	    --readTimeout  seconds to wait for a client message  default: 5
	    --deathTimeout seconds to wait to kill client        default: 3*readTimeout

	--boundHost can be an ip address, hostname, or -all-, where -all-
	means binding to all ip address on the current machine'

	for more info see: http://people.apache.org/~pmuellr/weinre/



## doc

http://docs.build.phonegap.com/en_US/debugging_remote_debugging_tools.md.html#Remote%20Debugging%20Tools


http://dl.dropbox.com/u/2192156/Papers/PhoneGap-Day-2012-US/index.html

http://www.youtube.com/watch?v=HEqwnpLYnI0&feature=youtu.be


## friends of weinre

PhoneGap Build	

-	https://build.phonegap.com/docs/phonegap-debug

Toura Mulberry	

-	http://mulberry.toura.com/blog/2011/11/14/hosted-weinre/

AppLaud	

-	http://applaudcloud.com/applauddoc.html#navbar-debug

jsFiddle	

-	http://doc.jsfiddle.net/use/remote_debugging.html

trigger.io	

-	https://trigger.io/catalyst/

WorkLight	

-	http://www.worklight.com/product/whats-new/release-4.2

Adobe Shadow	

-	http://labs.adobe.com/technologies/shadow/#features

rack-weinre	

-	https://github.com/irohiroki/rack-weinre/blob/master/README.md

Clutch.io	

-	https://twitter.com/ericflo/status/189472988146569218

weinre-rails	

-	http://rubydoc.info/gems/weinre-rails/frames

qooxdoo	

-	http://news.qooxdoo.org/debugging-mobile-apps-with-weinre

MIHTool	

-	https://groups.google.com/forum/?fromgroups=#!forum/mihtool



## runing

再目标目录执行

	weinre
	
然后打开网址，就可以了，太简单了

