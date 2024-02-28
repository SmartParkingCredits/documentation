# documentation

![Diagram1](diagram1.excalidraw.svg)

## Raspberry Pi

### SSH

```bash
ssh pi@raspberrypi.local
cd SPC-services
poetry env use python3
poetry install
cp example.env .env
poetry run python client qr
```
