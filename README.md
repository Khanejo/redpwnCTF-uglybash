# redpwnCTF-uglybash

This task required us to debug the bash script and get flag written in its comments

So, there are 2 ways to debug a bash script:

1) Add 'set -x' in starting of bash script and at end of bash script add line 'set +x', then normally run the script
2) Use '-x' parameter while running bash script, "bash -x cmd.sh"

Flag: flag{us3_zsh,_dummy}
