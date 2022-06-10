input=SinglyLinkedList.h_orig
output=
debug=
POET_HOME=../../../POET/trunk
POET=pcg

now:
	$(POET) $(debug) -L$(POET_HOME)/lib -pinputFile=testfiles/$(input) -poutputFile=$(output) -pspecFile=semantics/abstractions.spec abstractionAnalysis.pt

stack:
	$(POET) $(debug) -L$(POET_HOME)/lib -pinputFile=testfiles/$(input) -poutputFile=$(output) -pspecFile=semantics/abstractions.spec abstractionAnalysis.pt

queue:
	$(POET) $(debug) -L$(POET_HOME)/lib -pinputFile=testfiles/$(input) -poutputFile=$(output) -pspecFile=semantics/abstractions_queue.spec abstractionAnalysis.pt
