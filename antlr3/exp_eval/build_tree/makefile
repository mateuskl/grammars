GRAMMAR := Expr
APPLICATION := Test

all: generate compile

generate:
	java org.antlr.Tool $(GRAMMAR).g

compile:
	javac $(APPLICATION).java $(GRAMMAR)Lexer.java $(GRAMMAR)Parser.java

run:
	java $(APPLICATION)

clean:
	rm -f *.class

veryclean:
	rm -f *.class $(GRAMMAR)Lexer.java $(GRAMMAR)Parser.java $(GRAMMAR).tokens


