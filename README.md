## Build

- make sure `node` and `npm` are installed and up to date
- clone the repo
- run `npm install` inside the repo
- run `npm run gen` to regenerate the pcb file

## quirks

Ergogen's fillets are a little silly and will depending on your settings create little circles around some corners of your outline.
There doesn't seem to be any problem with just deleting them in KiCAD after the PCB generation, so just do that after running 
the generator.