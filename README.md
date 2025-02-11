## ezButton Library for Arduino, ESP32, ESP8266...
This library is designed to make it easy to use push button, momentary switches, toggle switch, magnetic contact switch (door sensor)..​. It is easy to use for not only beginners but also experienced users.

__ezButton__ stands for __Easy Button__

Features
----------------------------
* Uses the internal pull-up resistor by default to avoid the floating value
* Supports debounce to eliminate the chattering phenomenon
* Supports the pressed and released events
* Supports the counting (for FALLING, RISING and BOTH)
* Easy to use with multiple buttons
* All functions are non-blocking 
* Support internal pull-up/pull-down, external pull-up/pull-down

Available Examples
----------------------------
* [01.SingleButton](https://arduinogetstarted.com/library/button/example/arduino-single-button)
* [02.SingleButtonEvents](https://arduinogetstarted.com/library/button/example/arduino-single-button-events)
* [03.SingleButtonDebounce](https://arduinogetstarted.com/library/button/example/arduino-single-button-debounce)
* [04.SingleButtonAll](https://arduinogetstarted.com/library/button/example/arduino-single-button-all)
* [05.MultipleButtonAll](https://arduinogetstarted.com/library/button/example/arduino-multiple-button-all)
* [06.ButtonCount](https://arduinogetstarted.com/library/button/example/arduino-button-count)
* [07.ButtonArray](https://arduinogetstarted.com/library/button/example/arduino-button-array)


Available Functions
----------------------------
* setDebounceTime()
* getState()
* getStateRaw()
* isPressed()
* isReleased()
* setCountMode()
* getCount()
* resetCount()
* loop()

References
----------------------------
* [ezButton Library Reference](https://arduinogetstarted.com/tutorials/arduino-button-library)

NOTE:
----------------------------
* If you are using the [button module](https://www.amazon.com/dp/B0DQ3WM7K1), set the pin to input mode with external pull-down resistor using `ezButton button(pin, EXTERNAL_PULLDOWN)`. In this configuration, the module outputs **LOW** when the button is not pressed and **HIGH** when the button is pressed.
