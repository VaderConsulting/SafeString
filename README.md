# SafeString

A Safe, Static String library to replace Arduino String, plus non-blocking Serial I/O, I/O buffering, loopTimer and millisDelay. See README.md for revision notes. This library implemnents Safe (static) Strings which never cause reboots and has extensive debugging messages. Includes SafeStringReader: non-blocking tokenizing text reader, BufferedOutput: non-blocking text output, BufferedInput: extra buffering for text input, loopTimer: track of the maximum and average run times for the loop, PinFlasher: non-blocking flashing on an output Pin and millisDelay: a non-blocking delay, with single-shot, repeating, restart and stop facilities. Original author: Matthew Ford. This is Dave Robinson's working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 4.1.15. Upstream: <https://github.com/PowerBroker2/SafeString>.

**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SafeString` | C++ / Arduino | library | A Safe, Static String library to replace Arduino String, plus non-blocking Serial I/O, I/O buffering, loopTimer and millisDelay |
| `OBD_Processor` | C++ / Arduino | example sketch | `examples/OBD_Processor/OBD_Processor.ino` |
| `SafeStringReader_Assign` | C++ / Arduino | example sketch | `examples/SafeStringReader_Assign/SafeStringReader_Assign.ino` |
| `SafeStringReader_Cmds` | C++ / Arduino | example sketch | `examples/SafeStringReader_Cmds/SafeStringReader_Cmds.ino` |
| `SafeStringReader_CmdsTimed` | C++ / Arduino | example sketch | `examples/SafeStringReader_CmdsTimed/SafeStringReader_CmdsTimed.ino` |
| `SafeStringReader_GPS` | C++ / Arduino | example sketch | `examples/SafeStringReader_GPS/SafeStringReader_GPS.ino` |
| `SafeStringReader_flushInput` | C++ / Arduino | example sketch | `examples/SafeStringReader_flushInput/SafeStringReader_flushInput.ino` |
| `SafeStringStream_testdata` | C++ / Arduino | example sketch | `examples/SafeStringStream_Tests/SafeStringStream_testdata/SafeStringStream_testdata.ino` |
| `sfStream` | C++ / Arduino | example sketch | `examples/SafeStringStream_Tests/sfStream/sfStream.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/SafeString`). Open any `examples/*.ino` from the Arduino IDE.

## Attribution and provenance

- **Original author / maintainer:** Matthew Ford
- **library.properties name:** SafeString
- **Version:** 4.1.15
- **Upstream URL:** <https://github.com/PowerBroker2/SafeString>
- **Category:** Data Processing
- This repository is Dave Robinson's working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a VaderConsulting MIT wrapper and does not replace upstream terms.
