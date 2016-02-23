How to run
==========

`gradle appRun`

Then open `http://localhost:8080/gradle-gretty-demo/`

Note
----

`appRun` is provided by `gretty` plugin, replace the `jettyRun` from gradle `jetty` plugin.

Gradle `jetty` plugin uses `jetty:6.1.25` which is pretty old and doesn't support servlet 3.x.
 
If we want to use newer version of jetty, we have to use another plugin like `gretty` here.

For now, gretty is using `jetty 9` by default, but we can change it in `gretty` block in `build.gradle` file. In this example, we change it to use jetty 8.

<https://github.com/akhikhl/gretty>
