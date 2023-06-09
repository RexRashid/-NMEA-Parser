| Supported Targets | ESP32 | ESP32-C2 | ESP32-C3 | ESP32-S2 | ESP32-S3 |
| ----------------- | ----- | -------- | -------- | -------- | -------- |

# NMEA Parser (v2.1)
It is an NMEA Parser libray with an example implementation. To understand/modify the code, please refer to file [README.md](main/README.md) in [main](main) folder.

## How to use with esp32
Open esp-idf and navigate to the project terminal. Attach Esp32 and use commands:
`idf.py buiild` 
`idf.py -p (PORT) flash monitor`


## Folder contents
This project contains one source file in C language [main.c](main/main.c) and one library file [NMEA-parser.h](main/NMEA-parser.h). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt
├── sdkconfig
├── main
│   ├── CMakeLists.txt
    ├── NMEA-parser.h
│   └── main.c
└── README.md                  This is the file you are currently reading
```