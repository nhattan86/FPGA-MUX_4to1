# FPGA-MUX_4to1

This VHDL code implements a **4-to-1 Multiplexer** using a hierarchy of three 2-to-1 multiplexers.

- **Inputs**:
  - `A`, `B`, `C`, `D`: Four single-bit data inputs.
  - `s`: A 3-bit select signal.
- **Output**:
  - `Y`: A single output that represents one of the four inputs based on the select signal `s`.

- **Functionality**:
  - The multiplexer selects one of the inputs (`A`, `B`, `C`, or `D`) depending on the value of `s`:
    - When `s = "000"`, `Y` is set to `A`.
    - When `s = "001"`, `Y` is set to `B`.
    - When `s = "010"`, `Y` is set to `C`.
    - When `s = "011"`, `Y` is set to `D`.
  
This 4-to-1 multiplexer is essential in digital circuits where four potential sources need to be selected using a 3-bit control signal. By combining 2-to-1 multiplexers, the design is modular and can be easily scaled for larger multiplexers.

https://www.youtube.com/watch?v=ARqWnyrHsmU&t=11s
