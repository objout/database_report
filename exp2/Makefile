build/main.pdf: preamble.tex main.tex content.tex build/main.toc
	mkdir -p build
	xelatex -shell-escape -output-directory=./build main.tex

clean:
	rm -rf build/*.log build/*.aux build/*.out build/_minted-main
