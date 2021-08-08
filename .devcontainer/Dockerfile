FROM qmcgaw/latexdevcontainer
USER root

# install dependencies
RUN apt-get update && apt-get install -y \
  texlive-bibtex-extra \
  texlive-binaries \
  texlive-extra-utils \
  texlive-font-utils \
  texlive-fonts-recommended \
  texlive-formats-extra \
  texlive-lang-english \
  texlive-lang-european \
  texlive-lang-german \
  texlive-latex-base \
  texlive-latex-extra \
  texlive-latex-recommended \
  texlive-luatex \
  texlive-pictures \
  texlive-generic-extra \
  texlive-fonts-extra \
  python-pygments && rm -rf /var/lib/apt/lists/*

USER vscode