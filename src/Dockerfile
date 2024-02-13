FROM sharelatex/sharelatex:4.2.2

RUN tlmgr update --self --all
# install full latex packages, takes VERY VERY long time
RUN tlmgr install scheme-full

ARG SRC_PATH

COPY ${SRC_PATH}/AuthenticationManager.js /overleaf/services/web/app/src/Features/Authentication/AuthenticationManager.js
COPY ${SRC_PATH}/LaunchpadRouter.js /overleaf/services/web/modules/launchpad/app/src/LaunchpadRouter.js
