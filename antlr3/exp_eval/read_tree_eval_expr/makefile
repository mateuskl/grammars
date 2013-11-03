GRAMMAR1 := Expr
GRAMMAR2 := Eval
APPLICATION := Test

all: generate compile

generate:
	java org.antlr.Tool $(GRAMMAR1).g
	java org.antlr.Tool $(GRAMMAR2).g

compile:
	javac *.java

run:
	java $(APPLICATION)

clean:
	rm -f *.class

veryclean:
	rm -f *.class $(GRAMMAR2)Lexer.java $(GRAMMAR2)Parser.java $(GRAMMAR2).tokens $(GRAMMAR1)Lexer.java $(GRAMMAR1)Parser.java $(GRAMMAR1).tokens


