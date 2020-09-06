# homebridge-squeezebox

I am working on this - let's see what comest out of it.

Work in progress, may or may not work for you.

Example config.json

```
{
	"bridge": {
		"name": "Homebridge",
		"username": "CC:22:3D:E3:CE:30",
		"port": 51826,
		"pin": "031-45-154"
	},
	"platforms": [
		{
			"platform": "Squeezebox",
			"name": "Squeezebox",
			"host": "127.0.0.1",
			"port": 9000,
			"username": "username",
			"password": "password"
		}
	}
}
```

host/port for your Logitech Media Server