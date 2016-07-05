# xhgui

Simple xhgui webserver for connecting to a remote mongodb server populated with profiles.

This does not do any profiling for you, is only used to view profile data.



## Example Use
```
docker run -e MONGO_HOST_IP=127.0.0.1 -p 80:80 craigmcmahon/xhgui
```