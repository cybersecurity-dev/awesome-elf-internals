<div align="center">
    <p align="center">
        <a href="https://wiki.osdev.org/ELF">
        <details>
           <summary>ELF FILE MAP</summary>
          <img width="100%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/ELF_internals.jpg" />
        </details>
        </a>
    </p>

# **`Awesome`** [ELF](https://wikipedia.org/wiki/Executable_and_Linkable_Format) (Executable and Linkable [Format](https://gabi.xinuos.com/)) Internals [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]() 
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

## ELF X-Ray

```mermaid
mindmap
  root((ELF Internals))

    ELF Header
      Magic Number
      Architecture
      Endianness
      Entry Point
      File Type
      Offsets

    Program Headers
      Loadable Segments
      Memory Mapping
      PT_LOAD
      PT_INTERP
      PT_DYNAMIC
      PT_NOTE

    Sections
      .text
      .data
      .rodata
      .bss
      .plt
      .got
      .dynamic
      .init
      .fini

    Symbol Information
      Symbol Table
      String Table
      Relocations

    Dynamic Linking
      libc.so
      ld-linux.so
      GOT
      PLT

    Runtime View
      Stack
      Heap
      Data Segment
      Code Segment

    Security Analysis
      Packers
      Obfuscation
      Malware Detection
      IoT Malware

    Reverse Engineering
      readelf
      objdump
      strings
      nm
      Ghidra
      IDA Pro
```

## Miscellaneous Tools

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-elf-internals/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-elf-executable-and-linkable-format-internals-)
