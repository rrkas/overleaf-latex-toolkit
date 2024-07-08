bin/up

bin/shell
    wget https://mirror.ctan.org/systems/texlive/tlnet/update-tlmgr-latest.sh
    sh ./update-tlmgr-latest.sh -- --update
    tlmgr install scheme-full


