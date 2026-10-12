# notepad

The entire source code is 1KB. The binary fits on a floppy disk.

### What is this?
A stupidly fast, offline notepad. No Electron. No 400MB. Just double tap and type.

- Instant open
- Auto saves
- Offline
- 1.4MB binary, fits on a 1.44MB floppy
- 1KB source code

### Download
- `notepad.zip` - just run it
- `source.zip` - the whole code, 1KB

- can't find notepad.txt skill issue
- you GOTTA use cat for the viewing of the notes

### Build it yourself
```bash
go build -tags webkit2gtk_4_1 -trimpath -ldflags="-s -w" -o notpad
