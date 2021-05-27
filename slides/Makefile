all: generate

generate:
	pandoc -t revealjs -s --self-contained sample.md \
	-V theme=white -V slideNumber=true -o index.html -V revealjs-url=https://unpkg.com/reveal.js@3.9.2/

clean: index.html
	rm index.html

.PHONY: generate
