# Pitchfork [![Build Status](https://travis-ci.org/PacificBiosciences/pitchfork.svg)](https://travis-ci.org/PacificBiosciences/pitchfork)
Prototyping github source building while having a dumb file (Makefile) to describe a software component.

    make init
    make blasr PREFIX=/opt/mybuild             # if you want to build your own blasr
    bash --init-file /opt/mybuild/setup-env.sh # either to use the build in the sub-shell
    source /opt/mybuild/setup-env.sh           # or     to use the build in current shell 

For more information, please visit the [wiki page](https://github.com/PacificBiosciences/pitchfork/wiki)
