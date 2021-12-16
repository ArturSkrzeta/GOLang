# GOLang
+ compiled language - that's why its so fast - compiling a source code into  a lower level language in executable binary file - we can run it without go when compled into exe file
+ mostly for server side apps - APIs or website backends
+ concurrency support
+ packages are directories containting go files called modules - we can use multiple go files within one program
+ func main() {} - entry point of a programm
+ go build command - takes source code and wrap it up into an executable file - and we can give that executable file to someone else to run it
+ strongly and staticaly typed language - we need to declare and define a type of each variable before using it - 
var name string = "Artur"
var pos_num uint = 3   - uint accepta any positive whole number
name := "Artur"   - with this syntac we don;t need to provide a data type
+ in go tehere is an error when you define a variable and you don't use it further in the code
+ fmt.printf("Hello %v, what is up", name) - %v placeholder for a variable
+ & references memory address location of a given variable - every single variable is a label of unit of storage in computer's RAM (Random Access Memory)
+ fmt.Scan(&name) - scan function requires the memory location of a variable to asing a value to it
+ println goest to next line afterwards, printf stays at the same line
+ struct is your own custom type like a class
+ pointer:
x := 7
y := &x  -- y is equl to a pointer (memory address) of x
we  can change the value of x through the pointer of y
passing pointer to a function we take advantage of  changing  value through a reference
if we don't pass a pointer to a function, the function can change variable's value only wihitn it own scope
variable is passed by valye by default
when we pass an object to a function withut a ponter then whta is passed over is a copy of this object - any changes to its properties wont be reflected within main()
+ channels are the way for go routines to communicate with each other
