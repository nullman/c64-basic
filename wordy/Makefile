.RECIPEPREFIX = >

all: wordy.prg

wordy.prg:
> cat wordy.bas | tr '[A-Z]' '[a-z]' > wordy.tmp
> petcat -w2 -o wordy.prg -- wordy.tmp

clean:
> rm -f *.prg *.tmp
