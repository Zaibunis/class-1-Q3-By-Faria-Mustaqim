#inner working of python :

#who created in which son
#ide integrated development environment
#cursor
#python --version , py --version
#hardware se bat krne ke lye binary language ko dekhna parega 
#assemly kya hote , kese communicate krte he
#main.py top-level file he
#python ek interpreted language he yani (line by line)
#: replacement he curly braces joke function me hote hen
#code ko track krne kelye 'git' use hota he
#underscore ka mtlb internallly kam ho raha he

#--two types of programming language:
implicit & explicit
implicit (tyep casting execution hote he jo hme nzar nhi ate)
expicit (type import krne ho ya koi bhi cheez importkrne ho)
python implicit type language (type casting behind the scene hote he , internally hote he)

-----------------------
#.pyc compiled python (frozen binaries)
--pycache--
c python main ko uthane ke binary language me onvert krrha he r oske cecntre me ek step byte code he
|              |           /
source change  version  compiled python
main.cpython-311.pyc
famouse variant of python is c python
---------------------

generated file is because of the import 

#type define best practice

#ctrl + / commit


--#execution of hello world
internally working of python
convert byte code

python vm (virtual machine)
byte code(mostly hidden) and machine code are different things

properties of byte code :

BYTE CODE: (low level & platform independent) -> ye srf python ki virtual machine understand krskta he then binary code me convert me hota he (0:false , 1:true)

compile the code into byte code '.py'

byte code is not the machine code

byte code is faster because the code is stored in cache

#--python virtual machine (pvm):
code iteration (always running loop) 
run time engine(always running , executes and cnvert into binary languge , communicate to computer)
|
also known as python interpreter
ryme dal invented node.js compuer se bahar java ko run krske

#----tpu(Tensor processing unit)
#----Cpu(Control processing unit)
#----Gpu(Graphical processing unit)

#----------Data Types of python
string(str)->abc->textual value
tuples(tuples)->collection of data ,  imputable
integer(int)->numbers
boolean(bool)->true or false (t and f capital)
dictionary (dictionary)->object->key and value
float(float)->decimals numbers
list(list)->array (positive->left to right & negative ->right to left(-1 se start hote he) indexing)
set (set)->unique value ->repeated number arahae like 1224555 ->remove the repeted number unique data
frozen set (frozenset)->change nhi hita
none(NoneType)

mutable -> chnge ho kste he
imputable ->chnge nhi ho skte

interpreted dynamic language (python)

naming convention:
snake cases
body define(tab button or four spaces bcz it will cause indentation error)

#--pep 8

