To help us fairly evaluate your capabilities and fit for the role we have in mind and also to give you an idea of the typical kind of assignments you will be undertaking, we have provided a simple problem for you to solve.

Write a test program for an ESP32 module with the following features.

1. The program initializes a UART with no parity, but with hardware flow control.
2. The program initializes a buffer of 128 bytes of random characters.
3. The program installs a UART driver with an event queue.
4. The program creates a transmit task that uses a UART_DATA_BREAK event from the UART driver to refill the transmit buffer from the random character buffer and sleeps till the next event.

Please create a project on GitHub for your solution and provide us with a link. Please ensure that your code runs on a basic ESP32 module before you submit your solution.

Feel free to write to [work@iotready.co](mailto:work@iotready.co) with any questions. We are excited to see your solution and potentially joining our team!