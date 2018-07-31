# munin-plugins

I have some plugins for my network home.

# huawei_traffic & huawei_traffic2

This plugins tested with Huawei HG8245H. This make graph for each ethernet connection in multiple images or on single image.

## Example

![alt text](screenshots/huawei_traffic2-day.png?raw=true "Single Image")

## Settings

- plugin-conf.d/munin-node

	[huawei_traffic*]
	env.host 10.0.0.1
	env.username user
	env.password pass