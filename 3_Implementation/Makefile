JFLAGS = -g
JC = javac
.SUFFIXES: .java .class
.java.class:
        $(JC) $(JFLAGS) $*.java
CLASSES = OnlineTest.class

default : classes

classes: $(CLASSES:.java=.class)

clean:
        $(RM) *.class