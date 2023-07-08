.RECIPEPREFIX = >

all: helloworld.prg

helloworld.prg:
> cat helloworld.bas | tr '[A-Z]' '[a-z]' > helloworld.tmp
> petcat -w2 -o helloworld.prg -- helloworld.tmp

clean:
> rm -f *.prg *.tmp
