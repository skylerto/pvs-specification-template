# PVS Specification Template

This repository is to include the project setup and structure for a pvs specification.

## Structure

### Time.pvs
Time.pvs is a construct to represent a specified timing resultion. I should be used when ever a sense of time is needed.

### top.pvs
Include all specifications within this file.  
To provide a proof report execute.
```
proveit --importchain --clean top.pvs
``` unix

### bin
Contains scripts to aid in the development of the specification


## Usage

```
git clone https://www.github.com/skylerto/pvs-specification-template specification
``` unix

## License
MIT © Skyler Layne
