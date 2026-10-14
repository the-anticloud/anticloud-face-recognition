# Command Line Interface — FACE_RECOGNITION

**Upstream:** https://github.com/ageitgey/face_recognition

## Anticloud CLI

```bash
# Install
pip install anticloud-face-recognition

# Run offline with PAX inference
anticloud-face-recognition --offline --pax-local

# Run with AIOSS logging
anticloud-face-recognition --aioss-log ./ledger.jsonl

# Single binary (after build)
./face_recognition --config config.yaml
```

## Options

| Flag | Description |
| --- | --- |
| `--offline` | Disable all network calls |
| `--pax-local` | Use local PAX inference at 127.0.0.1:11434 |
| `--aioss-log PATH` | Write AIOSS audit chain to PATH |
| `--encrypt` | Enable AES-256 at rest for output files |
| `--gpu` | Force GPU inference |
| `--cpu` | Force CPU inference |
| `--config PATH` | Load configuration from YAML file |
