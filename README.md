# NAX_file
1.nax_test.cfg is for openocd
2.I seem to be unable to modify the starting address of sram through commands, so I modified the Python file located in the lite/doc/integration/soc_core. py file directory, line 234. To achieve the starting address of sram, I changed origin=self. mem_map ["sram"] to origin=0x40000000.
