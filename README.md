# ISP_Jump_server-frontiir-ssh #

Change .ppk to .pem
********************
$ puttygen *.ppk -O private-openssh -o *.pem

SSH Access
**********
alias console='sudo ssh -D1234 -i xxx.pem xxx@ip'

