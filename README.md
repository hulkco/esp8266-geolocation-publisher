# Geolocator

Tiny library for publishing geolocation related data over mqtt via PubSubClient.

## Usage

```c++
GeolocationPublisher geolocator( pubSubClient );

void setup() {
  ...
  geolocator.setup("some/mqtt/topic");
  ...
}

void loop() {
  ...
  geolocator.loop();
  ...
}
```

## Running Tests

```bash
./run-tests.sh
```
