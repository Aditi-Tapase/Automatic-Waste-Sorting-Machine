The amount of waste we generate globally is growing rapidly and we must find efficient ways
to manage it. Automatic waste sorting machines have emerged as a promising solution to
streamline the waste sorting process and promote recycling. In this project, we propose the
implementation of an automatic waste sorting machine using Edge Impulse, a platform for
developing machine learning models for edge devices. The proposed waste sorting machine
classifies different types of waste materials, such as paper, plastic, metal, and glass, by using
images. We collect and preprocess a diverse dataset of waste samples, leveraging the
capabilities of Edge Impulse, to ensure the representation of real-world scenarios. With Edge
Impulse's intuitive interface and tools, we optimize the trained model for deployment on edge
devices like microcontrollers or development boards. Integrating this model with the waste
sorting machine hardware enables real-time classification of waste materials, facilitating
efficient sorting and recycling processes. Experimental results demonstrate significant
improvements in sorting accuracy, efficiency, and resource recovery rates compared to manual
sorting processes. The automatic waste sorting machine achieves a recycling rate of over 90%,
substantially reducing the amount of waste destined for landfills or incineration. Moreover, the
system's modular design facilitates seamless integration with existing waste management
infrastructure, ensuring compatibility and scalability across diverse operational environments.
Keywords: Edge Impulse, Edge Devices, Microcontrollers, Development boards.
SYSTEM REQUIREMENTS
The system requirements for a Automatic Waste Sorting Machine can be categorized into
hardware, software, and functional requirements. Here's a detailed breakdown:
4.3. Hardware Requirements
The waste sorting machine has several components, including the ESP32 Camera, Arduino
Nano, conveyor belt, and DC motors.
1. ESP32 camera: The ESP32 Camera is a module that combines the ESP32 microcontroller
with a camera sensor. It captures images of the waste items moving along the conveyor
belt. These images are processed using machine learning algorithms or image processing
techniques to identify and classify the materials. The ESP32's processing power and Wi-Fi
capabilities make it suitable for capturing and transmitting image data wirelessly to a
central processing unit for analysis.
2. Arduino Nano: The Arduino Nano serves as the brain of the waste sorting machine. It
controls various aspects of the machine's operation, such as receiving data from sensors,
controlling motors, and making decisions based on programmed logic or machine learning
algorithms. The Arduino Nano interfaces with sensors, such as the ESP32 Camera, to
collect data and trigger actions, such as activating the conveyor belt or controlling sorting
mechanisms based on the detected waste types.
3. Conveyor belt: The conveyor belt is a mechanical system used to transport waste items
through the sorting machine. It ensures a continuous flow of waste materials, allowing for
efficient processing and sorting. The conveyor belt is driven by one or more DC motors,
which move the belt at a controlled speed. The waste items are placed on the conveyor belt
at one end and are carried along its length, passing under the ESP32 Camera for
classification and sorting.
4. DC Motors: DC motors provide the necessary torque and speed control to move the
conveyor belt smoothly and precisely. The Arduino Nano controls the DC motors using
motor driver circuits or motor control modules, adjusting their speed and direction as
needed to maintain the desired flow of waste materials through the system. Additionally,
DC motors may be used to actuate sorting mechanisms such as mechanical shafts to divert
waste items into different collection bins based on their classification.
4.4. Software Requirements
Arduino IDE: The Arduino IDE, also known as Integrated Development Environment, is a
software tool used to write computer code and upload it to the physical board. Its simplicity is
one of the main reasons for the popularity of the Arduino board. Nowadays, being compatible
with the Arduino IDE is a primary requirement for a new microcontroller board. The Arduino
IDE has improved over the years, adding many useful features. You can now manage thirdparty libraries and boards from the IDE while still enjoying the ease of programming the board.
