Coinhive JavaScript Miner

API Reference

CONSTRUCTORS

CoinHive.Anonymous(siteKey [, options])
CoinHive.User(siteKey, userName [, options])
CoinHive.Token(siteKey, targetHashes [, options])

INSTANCE METHODS

.start([mode])
.stop()
.isRunning()
.isMobile()
.didOptOut()
.on(event, callback)
.hasWASMSupport()
.getNumThreads()
.setNumThreads(numThreads)
.getAutoThreadsEnabled()
.setAutoThreadsEnabled(enabled)
.getThrottle()
.setThrottle(throttle)
.getToken()
.getHashesPerSecond()
.getTotalHashes([interpolate])
.getAcceptedHashes()
