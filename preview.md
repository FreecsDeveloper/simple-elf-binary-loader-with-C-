hi everyone . this is a simple elf binary loader with C++ using libbfd library . The loader uses libbfd functions to parse binary, get sybmbol table for both
static and dynamic functions , and others . 

The loader will print a type of the binary , name of sections , their respective virtual base addresses , sizes , type , and of course the section names , 
also the import and export table . 
