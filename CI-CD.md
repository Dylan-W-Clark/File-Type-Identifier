# Magic Number File Identifier

A Python tool that identifies file types by reading their magic numbers (file headers), rather than relying on file extensions.

## Why This Matters

File extensions can be easily spoofed. This tool reads the actual binary signature of files to determine their true type - useful for:
- Malware analysis
- CTF challenges
- Digital forensics
- Verifying file uploads

## Usage
```
python magic_identifier.py file1.png file2.pdf suspicious.exe
```

## Currently Supports

- PNG images
- JPEG images  
- GIF images
- PDF documents
- ZIP archives

## Future Improvements

- Add more file signatures (executables, Office docs, archives)
- Hex dump output mode
- Recursive directory scanning
- Custom signature database
