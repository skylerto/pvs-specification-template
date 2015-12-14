# PVS Specification Template

[PVS](https://github.com/SRI-CSL/PVS) is a specification language with a strong theorum prover. This repository is to include the project setup and structure for a pvs specification.

## Structure

### Time.pvs
Time.pvs is a construct to represent a specified timing resultion. I should be used when ever a sense of time is needed.

### top.pvs
Include all specifications within this file.  
To provide a proof report execute.

```unix
proveit --importchain --clean top.pvs
```

### bin
Contains scripts to aid in the development of the specification


## Usage

```unix
git clone https://www.github.com/skylerto/pvs-specification-template specification
```

## License
MIT © Skyler Layne
