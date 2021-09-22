# Chirpanalytica

## Installation instructions

Tested for Python 3.8.5 (64-bit)

All scripts should be called from-directory, not with absulute paths: first go into the desired directory and then start the script/file, because of the use of relative paths throughout the project.

Used ports (all specifically Cloudflare-compatible): 8880 (python backend), 2052 (go backend)

Port 8888 represents internal dev-enviroment, can be activated by setting go-env variable to "DEV"