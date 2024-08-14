# NurtureCloud Fork Release Process

## Manually releasing

We could use the maven release plugin, but since this should be very short-term
just bump the version number and run maven release on the relevant module(s).

You'll want to use the `release` profile.