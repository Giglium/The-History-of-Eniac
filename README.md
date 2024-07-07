# The History of ENIAC

This repository contains an essay written for the course "Storia della Tecnologia e dell'Informazione" (History of Information Technology) as part of the Bachelor's Degree program at the University of Padua during the academic year [A.A. 2016/2017](https://en.didattica.unipd.it/off/2014/LT/IN/IN0513/000ZZ/INM0017608/N0).
Titled "The History of ENIAC" (La storia di ENIAC), this essay details the story of the world's first computer, the Electronic Numerical Integrator and Computer (ENIAC). As a pioneering machine, ENIAC marked a significant milestone in the history of technology and computing, revolutionizing the way calculations were performed and setting the stage for future advancements in the field.

> The essay was formatted using the [FIUP/Template-piano-di-lavoro-stage](https://github.com/FIUP/Template-piano-di-lavoro-stage) LaTeX template

## Prerequisites

- [TextLive](https://tug.org/texlive/)

## Compilation

```bash
git clone https://github.com/Giglium/The-History-of-Eniac.git
cd The-History-of-Eniac
pdflatex -interaction=nonstopmode -halt-on-error TheHistoryofEniac.tex
```

## Compilation with docker

```bash
git clone https://github.com/Giglium/The-History-of-Eniac.git
cd The-History-of-Eniac
docker run --rm -v $(pwd):/workdir texlive/texlive:latest pdflatex -interaction=nonstopmode -halt-on-error TheHistoryofEniac.tex
```

## References

- E. Accenti, Dalle Piramidi ai Microchip. Il Computer nella storia. Dal 4000 ac al 2000, S.l., Edizioni Ettore Accenti, 2015.
- K. Kempf (1961), Electronic Computers Within The Ordnance Corps, [FTP.ARL.ARMY.MIL](http://ftp.arl.mil/~mike/comphist/61ordnance/chap2.html)
- R. X. Cringely, Accidental Empires. How the Boys of Silicon Valley Make Their Millions, Battle Foreign Competition, and Still Can't Get a Date, Second Edition, London, Penguin Books, 1996
- S. McCartney, ENIAC. The Triumphs and Tragedies of the World's First Computer, New York, Walker Publish Company, Inc., 1999.
- W. Stallings, Computer Organization and Architecture Designing For Performance, Eighth Edition, Upper Saddle River, Pearson Education, Inc., 2006 ( Italian translation: Architettura e Organizzazione dei Calcolatori. Progetto e Prestazioni, Ottava Edizione, Pearson, 2010).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
