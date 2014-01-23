corebt
======

Core file writing tool (linux-specific).

This package installs corebt utility as core files writer.
Core files redirected into thir own directoryes under /var/log/core together
with some useful information, including stack trace.

Enable coredumps with

    ulimit -c unlimited

System-wide settings are in /etc/security/limits.conf and /etc/security/limits.d/*.

Test with

    sh -c 'kill -SEGV $$'


