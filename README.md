How to run
==========

`gradle appRun`

Then open `http://localhost:8080/gradle-gretty-demo/`

Note
----

`appRun` is provided by `gretty` plugin, replace the `jettyRun` from gradle `jetty` plugin.

Gradle `jetty` plugin uses `jetty:6.1.25` which is pretty old and doesn't support servlet 3.x.
 
If we want to use newer version of jetty, we have to use another plugin like `gretty` here.

<https://github.com/akhikhl/gretty>
