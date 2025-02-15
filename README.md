# RAM-DESIGN

**COMPANY**: CODTECH IT SOLUTIONS PVT.LTD

**NAME** :SAMYAK MANOJ PATIL

**INTERN ID** :CT06MVO

**DOMAIN** :VLSI

**BATCH DURATIOIN** :January 15th, 2025 to February 15th, 2025

**MENTOR NAME** :NEELA SANTHOSH KUMAR

**DESCRIPTION** :
    A simple synchronous RAM (Random Access Memory) module is a type of memory used to store data that can be read from or written to on a byte-by-byte basis. The synchronous nature means that the read and write operations occur in sync with a clock signal. This module is designed to read and write data in a predictable and orderly manner, based on the rising edge of the clock.

OPERATIONS IN RAM :
    1) Clock-Driven Operations:
        The read and write operations are controlled by a clock signal, ensuring that all actions happen synchronously .
    2) Write Enable Signal:
        The module has a write_enable signal. When this signal is active (high), the data presented on the data_in input will be written to the memory at the address                 specified by addr.
        If write_enable is low, no write operation occurs, but the module may still output data if a read operation is requested.
    3) Address Bus:
        The module uses an address input to specify the location in the memory where data will be read from or written to. The size of the address bus determines how many            locations can be addressed.
        For example, with a 4-bit address bus, the RAM can store data in 2^4 = 16 locations.
    4) Data Bus:
        The module has a data_in input for the data to be written and a data_out output for the data that is read from the memory. The size of the data bus (e.g., 8 bits)            defines the amount of data that can be read or written at one time.
    5) Memory Storage:
        The memory storage is typically implemented as a two-dimensional array, where each element corresponds to a memory location. The data at each location is stored in           registers (or combination of flip-flops) that hold the data for the duration of the memory operation.

WORKING OF RAM :
    1) Write Operation:
        When the write_enable signal is high, the data_in value is written into the memory location specified by the addr signal. This occurs on the rising edge of the clock.
    2)Read Operation:
        The module always outputs data from the memory location specified by addr. This occurs on the rising edge of the clock, regardless of the write_enable signal. If             write_enable is not active, no data is written, but the memory will still provide the data from the address location.
    3) Clocking:
        The memory operation occurs only on the clock's rising edge, which means that both reading and writing to the memory are synchronized to the clock signal. This               ensures consistency and avoids potential timing issues in larger designs.

**INTERNET RESOURCES USED**:
WEBSITES :
   https://www.lenovo.com/in/en/glossary/sd-ram/?orgRef=https%253A%252F%252Fwww.google.com%252F
   https://www.fpgakey.com/tutorial/section912?srsltid=AfmBOorT_ngVZmrvyUqm14Nt5qafJDoxmZDhRrRY9ovOPieUCFRe2A1r
   https://circuitdigest.com/microcontroller-projects/designing-of-ram-in-vhdl-using-modelsim

YouTube LINKS:
    https://youtu.be/7f50sQYjNRA?si=vnI8ZsWt9ndrR_92]
    https://youtu.be/a--rNdqtwCI?si=JeWZYLlKhMoV13rp
    
AI USED :
    CHAT GPT
    GEMINI

**OUTPUT **:
 










