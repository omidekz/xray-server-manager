# xray server manager

## Project contains following feature

- configuration templates
- configuration's runner script
- manage by cmd `./vmng`
- manage by telegram bot (development)
  - commit changes
  - users
  - add user
  - remove users
  - export link
## Run scrip usage

`./run configs/config-name.json`

** NOTE that `config-name` has to follow the following structure

`cluster-unique-name_target-port_rest_of_descriptions.json`

then you can do simple monitor by `docker stats`

it's recomended to use the `wondershaper` to limit the download/upload speed.
