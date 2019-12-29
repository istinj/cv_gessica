.PHONY : all latex clean distclean

TARGET=cv_trivelli_deu
SOURCE=$(TARGET).tex

all:
	xelatex $(SOURCE)
	xelatex $(SOURCE)

latex:all

clean:
	rm -f $(TARGET).aux $(TARGET).bbl $(TARGET).blg $(TARGET).log $(TARGET).brf $(TARGET).synctex.gz $(TARGET).out $(TARGET).glo $(TARGET).ist $(TARGET).gls $(TARGET).glg $(TARGET).bcf $(TARGET).run.xml

distclean:clean
	rm -f $(TARGET).pdf
