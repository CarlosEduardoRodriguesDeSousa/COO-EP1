
JFLAGS = -g
JC = javac
.SUFFIXES: .java .class
.java.class:
	$(JC) $(JFLAGS) $*.java

CLASSES = \
        Player.java \
        Score.java \
        Ball.java \

default: classes

classes: $(CLASSES:.java=.class)
