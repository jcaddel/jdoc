| | property | default<br>value | description |
|-|-|-|-|
| 1 | stp.http.request.wrap.bodies | false | Flag for controlling the wrapping of request bodies.  This makes it possible to read the request body more than once. That makes it possible to do additional things with the request body (eg log it, cache it, persist it, etc) |
| 2 | stp.http.request.cache.enabled | false | Flag for controlling the caching of http requests. Request body wrapping must be turned on if this flag is set. |
| 3 | stp.http.request.cache.max | 100,000 | Maximum number of http requests to cache in main memory.  This property only has meaning if http request caching is enabled|
| 4 | stp.http.request.persist.interval | 15m | This is the interval at which HttpLogPersister drains the cache and persists http requests to Blob Storage (S3 Bucket on PCF) |
| 5 | stp.http.request.attributes.prefix | none | Prefix for request attributes to include |
| 6 | stp.http.request.cookies.prefix | * | Prefix for cookies to include |
| 7 | stp.http.actuator.enabled | true | Turn summary statistics on/off (legacy actuator) |
