demos = forking forked sigsend sigrecv semlock semwait

XA=xa

all: ${demos}

clean:
	rm -f ${demos}
	rm -f *.lab

forking: forking.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R forking.a65 -LOSA2KERNEL -LLIB6502 -o forking)

forked: forked.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R forked.a65 -LOSA2KERNEL -LLIB6502 -o forked)

sigsend: sigsend.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R sigsend.a65 -LOSA2KERNEL -LLIB6502 -o sigsend)

sigrecv: sigrecv.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R sigrecv.a65 -LOSA2KERNEL -LLIB6502 -o sigrecv)

semlock: semlock.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R semlock.a65 -LOSA2KERNEL -LLIB6502 -o semlock)

semwait: semwait.a65
	(XAINPUT=../../include; export XAINPUT; ${XA} -R semwait.a65 -LOSA2KERNEL -LLIB6502 -o semwait)

