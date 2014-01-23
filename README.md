corebt
======

Core file writing tool (linux-specific).

This package installs corebt utility as core files writer.
Core files redirected into thir own directoryes under /var/log/core together
with some useful information, including stack trace.

Test with

    sh -c 'kill -SEGV $$'


