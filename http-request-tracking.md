| property | default<br>value | description |
|-|-|-|
| stp.http.request.wrap.bodies | false | If true, request bodies get wrapped, making it possible to read the request body more than once
  This makes it possible to do other things with it (log it, persist it, etc) |


<!-- If true, request bodies get wrapped, making it possible to read the request body more than once -->
  <!-- This makes it possible to do other things with it (log it, persist it, etc) -->
  <property key="stp.http.request.wrap.bodies">
    <value text="false" />
  </property>        
