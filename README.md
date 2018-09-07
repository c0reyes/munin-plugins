# munin-plugins

I have some plugins for my network home.

# huawei_traffic & huawei_traffic2

This plugins tested with Huawei HG8245H. This make graph for each ethernet connection in multiple images or on single image.

## Example

![alt text](screenshots/huawei_traffic2-day.png?raw=true "Single Image")

## Settings

- plugin-conf.d/munin-node

```
[huawei_traffic*]
env.host 10.0.0.1
env.username user
env.password pass
```

# ddwrt_load

This plugins get the load of dd-wrt micro. dd-wrt micro doesn't have snmpd server so with this plugin you can access with telnet and get the information.

## Example

![alt text](screenshots/ddwrt_load-day.png?raw=true "ddwrt load")

## Settings

- plugin-conf.d/munin-node

```
[ddwrt_load]
env.host 10.0.0.1
env.username user
env.password pass
```
