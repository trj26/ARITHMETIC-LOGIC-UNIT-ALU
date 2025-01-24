**COMPANY** - CODTECH IT SOLUTIONS.



**NAME** - TRUPTI RANJIT JAGTAP.



**INTERN ID** - CT08LCH.



**DOMAIN** - VLSI.
**BATCH DURATION** - JANUARY 20TH,2025 TO FEBRUARY 20th,2025. 
**MENTOR NAME** - NEELA SANTOSH KUMAR.
**DESCRIPTION OF TASK PERFORMED**
**Objective**: To design a Basic Arithmetic Logic Unit (ALU) capable of performing fundamental arithmetic and logical operations, including addition, subtraction, AND, OR, and NOT.

The design is implemented in VSCODE by the extension of verilog and installing verilog and tested for correctness using a set of predefined test cases.

"STEPS PERFORMED" include

**Requirement Analysis**: Identified the core operations required for the ALU: addition, subtraction, AND, OR, and NOT. Defined input and output specifications for the ALU. Two inputs A and B for binary operations. A single input A for unary operations like NOT. An operation selector signal (OpCode) to determine the desired operation. Output for the operation's result and a CarryOut signal for addition/subtraction if applicable.

**DESIGN IMPLEMENTATION**: Created a modular design to allow scalability and reuse. Implemented the following functional blocks: Addition Block: Used a binary adder (Ripple Carry Adder or any efficient method). Subtraction Block: Leveraged two's complement addition to perform subtraction. Logic Blocks: Designed basic gates for AND, OR, and NOT operations. Integrated all functional blocks using a multiplexer controlled by the OpCode.

**TESTING AND VERIFICATION**: Wrote testbench scripts to simulate the ALU in a hardware simulation tool. Tested for all possible combinations of inputs and operation codes to validate correctness. Verified the edge cases, such as overflow during addition or subtraction.

**DOCUMENTATION**: Provided detailed comments in the code explaining each module's functionality. Added performance analysis and possible improvements.

**UPLODING CODE TO GITHUB**: Organized the project into directories: 1)The ALU design file
                                                                     2)The testbench scripts and simulation results. 
                                                                     3)Added a README file 
                                                                     4)Uploaded the entire project repository to GitHub.

**OUTCOME**: A functional Basic ALU capable of performing addition, subtraction, AND, OR, and NOT operations with verified correctness and proper documentation.
