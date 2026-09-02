FROM debian:bookworm-slim

RUN apt-get update \
    && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
        ghostscript \
        lmodern \
        make \
        texlive-fonts-recommended \
        texlive-lang-portuguese \
        texlive-latex-extra \
        texlive-publishers \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /home/latex
