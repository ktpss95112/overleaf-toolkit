FROM sharelatex/sharelatex:4.2.2

RUN tlmgr update --self --all
# install full latex packages, takes VERY VERY long time
RUN tlmgr install scheme-full
