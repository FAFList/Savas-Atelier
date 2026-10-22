# Plant Monitor

Device will read the sensor data maybe calculate the historical data in order 
to get a happiness score and display it as a pet illustration on a display

## Sensors 

- Soil humidity sensor
- Air humidity and Temperature sensor (DHT11)

### Display
- Pet to describe the plan happiness score

## Project Structure

```bash
.
├── PlantMonitor.ino # Entrypoint
├── README.md
└── src # Library source C++
    ├── hello.cc
    └── plantlib.h
``` 

```cpp
// Include the library header
#include "src/plantlib.h"

void setup() {
  hello(); // Call library functions
}


void loop() {
  
}
```

The ArduinoIDE will compile all the required files for the project.

## Libraries

- [DHT11](https://github.com/adidax/dht11)

