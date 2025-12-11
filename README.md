# RAM-DESIGN

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HARINI T

*INTERN ID*: CT04DR2925

*DOMAIN*: VLSI

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

During my internship, I worked on designing and simulating a simple synchronous RAM module that supports both read and write operations, using Verilog HDL and an industry-standard Electronic Design Automation (EDA) tool. The purpose of this project was to deepen my understanding of memory architecture, synchronous data transfer, and clock-driven digital systems, while also strengthening my ability to verify hardware behaviour through simulation.The synchronous RAM module I developed was organized as an array of memory locations that stored data based on the rising edge of the clock signal. It included key inputs such as a clock, write enable (WE), read enable (RE), address lines, data input, and a data output bus. In synchronous RAM designs, both read and write actions occur strictly on the clock edge, ensuring predictable timing, high stability, and suitability for high-performance digital systems.When the write enable signal was asserted, the data on the input bus was written into the specified memory address at the clock’s rising edge, eliminating the possibility of accidental writes during signal glitches or unstable periods. Likewise, the read enable signal caused the RAM to output the stored data at the next rising edge, ensuring that the output always remained synchronized with the system timing. This behaviour highlighted how synchronous memory preserves data consistency and avoids hazards that typically arise in asynchronous circuits—an essential requirement for memory blocks used within processors and other digital architectures.After completing the Verilog design, I created a comprehensive testbench to verify functional correctness. The testbench generated a continuous clock signal, performed multiple write cycles with various address–data combinations, and executed corresponding read cycles to confirm data integrity. It also validated that the RAM retained its previous content when write enable was inactive and ensured that the output bus carried valid data only during read operations.With the module and testbench ready, I proceeded to simulate the design using the EDA tool provided during my internship. The tool efficiently handled compilation, syntax checking, and simulation execution. One of its most valuable features was the waveform viewer, which enabled me to observe clock transitions, address variations, write operations, and output responses in detail. By examining the waveform, I verified that write operations occurred precisely on the rising clock edge and that read operations produced correct data at the expected time intervals. The ability to zoom into specific timing regions and trace individual signal behaviours played a crucial role in thoroughly validating the RAM’s synchronous operation.I captured waveform results and included them in my documentation to clearly illustrate the read–write behaviour of the memory. This project greatly enhanced my understanding of synchronous memory design, timing coordination, and professional hardware verification methodologies. I am sincerely grateful to Codtech for giving me this valuable opportunity to strengthen my technical skills and gain meaningful, hands-on experience in digital system development and simulation.

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/79ee843d-2573-47b8-9690-45e276aec54d)
