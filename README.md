[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/ahmadmayahi/coronavirus-cli) 

## Corona Statistics CLI

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/501b6a840cc04e678ff4f883061a028b)](https://app.codacy.com/manual/keithwegner/coronavirus-cli?utm_source=github.com&utm_medium=referral&utm_content=keithwegner/coronavirus-cli&utm_campaign=Badge_Grade_Dashboard)[![Run on Repl.it](https://repl.it/badge/github/keithwegner/coronavirus-cli)](https://repl.it/github/keithwegner/coronavirus-cli)

Get the latest coronavirus statistics directly from the CLI.

> Please make sure that you have `Python 3` up and running on your machine.

![Global](https://i.imgur.com/r7e21Th.png) 

![Denmark](https://i.imgur.com/Juex7sH.png)

```bash
git clone git@github.com:ahmadmayahi/coronavirus-cli.git
cd coronavirus-cli
pip3 install -r requirements.txt

# Get the statistics
python3 corona.py

# Statistics for a specific country (alpha2 code)
python3 corona dk # Denmark
python3 corona us # United States
python3 corona au # Australia

# Make the script available globally
sh install.sh
corona
```
