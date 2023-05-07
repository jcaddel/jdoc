| | property | default<br>value | description |
|-|-|-|-|
| 1 | stp.http.request.wrap.bodies | false | If true, request bodies get wrapped in a cache.  This makes it possible to read the request body more than once. That makes it possible to do additional things with the request body (log it, cache it in memory, persist it, etc) |
| 2 | stp.http.request.cache.enabled | false | If true, http requests get cached in main memory (on each node). If this property is set to true, `stp.http.request.wrap.bodies` must also be true. |
| 3 | stp.http.request.cache.max | 100,000 | Maximum number of http requests to cache in main memory (per node).  This property only has meaning if http request caching is enabled  (`stp.http.request.cache.enabled=true`) |



<!-- If true, request bodies get wrapped, making it possible to read the request body more than once -->
  <!-- This makes it possible to do other things with it (log it, persist it, etc) -->
  <property key="stp.http.request.wrap.bodies">
    <value text="false" />
  </property>        
