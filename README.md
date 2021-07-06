# Pastel RPC Documentation Generator

This tool extracts and formats the help text for each of the Pastel RPC calls.  
Serve the generated html files.  

## How to generate docs

Ensure that you have Go installed and a working and running `pasteld` instance and that the `pastel-cli` executable is available in `/usr/bin/pastel-cli` (or update the absolute path to your pastel-cli executable in `src/generate_rpc_doc.go`). From the `src` directory simply run `go run generate_rpc_doc.go` and the documentation will be produced for all Pastel RPC calls and styled according to the template in `template.html`.

## License

License of the docs is MIT (see https://github.com/pastelnetwork/pastel), license of the scripts and webpage is also MIT ((C) 2021 Pastel Network)
