Static analysis tells you the behavior of the malware before you execute it.

# Detect Malicious Code

## VirusTotal

Search by file hash, etc.
https://www.virustotal.com/

## oleid

Detect malicious code in OLE files (Word, Excel, etc.)
`oleid filename`

# Get File Metadata

## exiftool

Get file metadata
`exiftool filename`

## olemeta

Get OLE file (Word, Excel, etc.) standard properties
`olemeta filename`

# Get Raw File Data

## strings

Get strings from file
`strings filename`

## xorsearch

Search for encoded strings in a file (XOR, ROT, etc.)
`xorsearch filename searchstring`

Search for embedded executables
`xorsearch -p filename`
