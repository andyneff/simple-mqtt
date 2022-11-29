This is a very simple example of a working MQTT server using the official `eclipse-mosquitto` image

**Warning**: This is not a secure example, no TLS configured

All you have to do is:

```
docker-compose up
```

As you will see in the output, this:

1. Sets a test username and password (no output visible)
2. Start the mosquitto server, and expose it externally to port 1883
3. Start a Subscriber (internally)
4. Run a test publish message (internally)
