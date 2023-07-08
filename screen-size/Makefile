.RECIPEPREFIX = >

all: screensize.prg

screensize.prg:
> cat screensize.bas | tr '[A-Z]' '[a-z]' > screensize.tmp
> petcat -w2 -o screensize.prg -- screensize.tmp

clean:
> rm -f *.prg *.tmp
