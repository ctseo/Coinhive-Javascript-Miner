Coinhive JavaScript Miner 

API Reference

	- Constructors
	
		# CoinHive.Anonymous(siteKey [, options])
		# CoinHive.User(siteKey, userName [, options])
		# CoinHive.Token(siteKey, targetHashes [, options]) 
    
	- Instance Methods
	
		# .start([mode])
		# .stop()
		# .isRunning()
		# .isMobile()
		# .didOptOut()
		# .on(event, callback)
		# .hasWASMSupport()
		# .getNumThreads()
		# .setNumThreads(numThreads)
		# .getAutoThreadsEnabled()
		# .setAutoThreadsEnabled(enabled)
		# .getThrottle()
		# .setThrottle(throttle)
		# .getToken()
		# .getHashesPerSecond()
		# .getTotalHashes([interpolate])
		# .getAcceptedHashes()
	
  Doc: https://coinhive.com/documentation/miner
