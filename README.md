# lnav-formats
Lnav - log navigation library parsing configuration. Specifically works for ns_server.debug|info.log and some of the others as well.

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [lnav-formats](#lnav-formats)
    - [Installation instructions:](#installation-instructions)

<!-- markdown-toc end -->


## Installation instructions:

1. clone repo
```bash
git clone https://github.com/bryandmc/lnav-formats.git
```

2. create necessary directories (if necessary)
```bash
mkdir -p ~/.lnav/formmats/installed
```

3. copy into correct directory
```bash
cp lnav-formats/ns_server.debug.json ~/.lnav/formats/installed/.
```

4. enjoy.
```bash
lnav ... (logfile.log)
```
