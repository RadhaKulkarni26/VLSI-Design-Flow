# VLSI Design Flow
- Very large scale integration (VLSI) is the process of creating an integrated circuit(IC) by combining thousands of transistors into a single chip.

- Design Flow in VLSI is a series or sequence of steps involved in making an IC.

- The below diagram shows the Design Flow in VLSI.

![VLSI Design Flow](https://user-images.githubusercontent.com/70748543/155379148-c9336879-c260-49d3-8336-257d61466539.jpeg)

- **System Specifications**: It is the first step in the design flow. The factors to be considered in this system specifications are performance, functionality, physical   dimensions, fabrications, technology, and design techniques.

- **Architectural Design**: The architectural design of VLSI will begin with main ideas with definitions of modules in terms of input, output, number of ALUs, Floating point units, number and structure of pipelines, and size of caches among others.

- **Functional Design**: In functional design, the area, power, and other parameters of each unit is estimated. The outcome of it is usually a timing diagram.

- **Logic Design**: In logic design control flow, word width, register allocation, arithmetic operations, and logic operations are derived and tested.
This description is called RTL description. It is expressed using Hardware Description Languages like VHDL and Verilog.

- **Circuit Design**: The Boolean expressions are converted into a circuit representation by taking into consideration the speed and power requirements of the original design.
Circuit Simulation is used to verify the correctness and timing of each component.
The circuit diagram shows the circuit elements (cells, macros, gates, transistors) and the interconnection between these elements. This representation is also called as a Netlist. A netlist can be created automatically from logic or RTL description by using logic synthesis tools.

- **Physical Design**: In physical design, the netlist is converted into a geometric representation called a Layout. The layout is created by converting each logic component into geometric. Connections are also represented as geometric patterns typically lines in multiple layers.
Physical Design is the most complex process.

- **Fabrication**: After layout and verification the design is ready for fabrication. Layout data is converted into photo-lithographic masks, one for each layer. Masks identify spaces on the wafer where certain materials need to be deposited, diffused, or even removed. Silicon crystals are grown and sliced to produce wafers.

- **Packaging and Testing**: The wafer is fabricated and cut into individual chips in the fabrications process. Then chip is packed ad tested.
