# volume# CS50 – Volume

## Description

This program modifies the volume of a `.wav` audio file by scaling each audio sample by a specified factor.

## How it works

The program:

1. Takes an input file, an output file, and a scaling factor as command-line arguments
2. Copies the WAV header to preserve the original file format
3. Reads, scales, and writes each audio sample to create a new audio file with adjusted volume

## Usage

```bash
make volume
./volume input.wav output.wav factor
```

## Example

```
./volume input.wav output.wav 2.0

This doubles the volume of input.wav and saves the result as output.wav.
```

## Concepts

- File I/O
- Command-line arguments
- Binary file processing
- Audio sample manipulation
- Buffers
- Integer types (int16_t, uint8_t)
- Reading and writing files with fread and fwrite
- Type conversion with atof
