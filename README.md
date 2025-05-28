# Lab8-Starter

Eric Nguyen

Graceful degradation is we start with max technology and address lower levels such that the whole application works when there are faults in smaller sections of functionality. In our lab, service workers allpw offline access by caching files.  By building our design through GD, we can allow the code to fall back onto back up code in the event that the service workers fail to follow through.  If the service workers in our lab don't activate, then the code will cause the JS file to fetch the recipes through the URLs.