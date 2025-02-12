# What does `java.lang.IllegalStateException: Multi threaded access requested by thread Thread[Server thread,7,main] but is not allowed for language(s) js.` mean when I reload the plugin?

This error message may appear when you reload the YamJS plugin and is usually isolated to reloading the YamJS GraalVM Context. It does not typically cause any errors or issues within YamJS, so you can safely ignore the message. However, we understand that this is not an ideal situation. If you have suggestions for how to improve the plugin to avoid this error message, please feel free to submit a pull request with your changes.

# Why are there two jars, YamJS-paper and YamJS-paper-legacy?

Newer users starting from scratch should aim to use YamJS-paper. Users that are transitioning from a Grakkit codebase (with an existing production server) can leverage YamJS-paper-legacy, as it'll preserve the "grakkit" plugin name. This allows existing data to continue to function, without having to migrate everything over to a new plugin.
