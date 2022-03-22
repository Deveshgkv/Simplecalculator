# Simplecalculator/*
Simple calculator
Ephraim Raj Feb 16 2016

This program implements 
basic expression calculator.

Imput from cin, output out of cout.

Grammar of input is 
Calculate :
	Statement  
	Print
	Quit
	Help
Print :
	newline
	;
Quit :
	quit
Help
	help
Statement :
	Declaration
	Expression
Declaration :
	let name = expression
	const name = expression
Expression :
	Assignment
	Term
	Expression + Term
	Expression - Term
	Expression print Expression  
Assignment : 
	Name = expression
Term :
	Primary
	Term * Primary
	Term / Primary
	Term % Primary
Primary :
	+Primary
	-Primary
	(Expression)
	{Expression}
	Name
	Number
Number : 
	Floating-point literal
Name :
	string literal
Input comes from a Token_stream called ts.

*/
