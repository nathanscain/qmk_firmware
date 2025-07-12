.phony: all clean compile svg png

all: clean compile svg png

clean:
	qmk clean

compile: clean
	qmk compile -kb keebio/iris_lm/k1 -km nathanscain

svg:
	keymap -c svg-config.yml draw svg.yaml > keymap.svg

png: svg
	magick -background '#0E1117' keymap.svg keymap.png
