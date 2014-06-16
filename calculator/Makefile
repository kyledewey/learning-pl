all: calculator calculator_with_macros
	echo Made all

calculator_with_macros:
	rubber --pdf calculator_with_macros

calculator:
	rubber --pdf calculator

clean: 
	rm calculator.pdf; rubber --clean calculator
