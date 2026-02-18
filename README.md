# Asar
[Asar](https://github.com/electron/asar) packager & extractor written in Rust.

## Command Line Interface
`asar [SUBCOMMAND]`

### Subcommands
`extract <ARCHIVE> <DEST>`  
Extract all files from an asar archive

`extract-file <ARCHIVE> <DEST>`  
Extract a single files from an asar archive

`list <ARCHIVE>`  
List all files included in an asar archive

`pack <DIR> <DEST>`  
Pack a directory into an asar archive