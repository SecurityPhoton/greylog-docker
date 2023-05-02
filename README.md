# greylog-docker
Docker compose for Greylog

This repo is for running greylog in docker using docker compose. Populate the .env file with your settings. Currently the sha256 is set to the word - password

Use command to generate disired password

``` echo -n 'your_secret' | sha256sum ```
