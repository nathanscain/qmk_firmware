.phony: all clean compile flash svg png

all: clean compile svg png

clean:
	qmk clean

compile:
	qmk compile -kb keebio/iris_lm/k1 -km nathanscain

flash: compile
	qmk flash -kb keebio/iris_lm/k1 -km nathanscain

svg:
	keymap -c svg-config.yml draw svg.yaml > keymap.svg

png: svg
	magick -background '#0E1117' keymap.svg keymap.png
