all: generate compile

generate:
	java org.antlr.Tool Expr.g

compile:
	javac Test.java ExprLexer.java ExprParser.java

run:
	java Test

