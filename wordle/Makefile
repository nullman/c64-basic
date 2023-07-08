.RECIPEPREFIX = >

all: wordle.prg

wordle.prg:
> cat wordle.bas | tr '[A-Z]' '[a-z]' > wordle.tmp
> petcat -w2 -o wordle.prg -- wordle.tmp

clean:
> rm -f *.prg *.tmp
