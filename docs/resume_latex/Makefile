
SAMPLES = resume.tex resume_software.tex resume_vision.tex resume_hardware.tex resume_simulation.tex

PDF = ${SAMPLES:%.tex=%.pdf}

all:  ${PDF}


%.pdf:  
	pdflatex $<
	pdflatex $<


resume.pdf: resume.tex
resume_hardware.pdf: resume_hardware.tex
resume_software.pdf: resume_software.tex
resume_vision.pdf: resume_vision.tex
resume_simulation.pdf: resume_simulation.tex

clean:
	$(RM)  *.log *.aux *.out *.pdf


