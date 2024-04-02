# NAX_file
1.nax_test.cfg is for openocd  

2.I seem to be unable to modify the starting address of sram through commands, so I modified the Python file located in the lite/doc/integration/soc_core. py file directory, line 234. To achieve the starting address of sram, I changed 
```
origin=self. mem_map ["sram"] 
```
to 
```
origin=0x40000000.
```
3.In order to save your time, I have sent you all the necessary files. You can directly add the top file sipeed_tag_primer. v and other configuration files to any EDA software to run  or simulate it.  
