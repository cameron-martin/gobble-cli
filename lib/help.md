
  gobble-cli version <%= version %>
  ===========================================

  Usage:
    gobble -h | --help
    gobble -v | --version
    gobble [serve] [-p|--port <port>] [-e|--env <env>] [-c|--config <config>]
    gobble build [-f|--force] [-e|--env <env>] [-c|--config <config>] <dest>
    gobble watch [-f|--force] [-e|--env <env>] [-c|--config <config>] <dest>

  Options:
    -h --help      Show this message
    -v --version   Show gobble-cli version
    -p --port      Development server port [default: 4567]
    -f --force     Remove existing contents of <dest>
    -e --env       Environment setting [default: development]
    -c --config    Gobblefile name [default: gobblefile]
    <dest>         Destination directory for `gobble build`

  For more information visit https://github.com/gobblejs/gobble/wiki
