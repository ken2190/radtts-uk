# Ukrainian RADTTS/RADTTS++ and HiFiGAN model

This repository contains links to models:

- Decoder model for RADTTS
- Decoder model for RADTTS++
- Pretrained model for RADTTS
- Pretrained model for RADTTS++ with AGAP config
- Pretrained model for RADTTS++ with BGAP config 
- Pretrained model for RADTTS++ with DAP config

Voices are from [Open Source Ukrainian Text-to-Speech datasets](https://github.com/egorsmkv/ukrainian-tts-datasets)

These models have three voices:

- Lada
- Tetiana
- Mykyta

## Demo

### Lada

### Tetiana

### Mykyta

## How to run?

Clone the repository https://github.com/egorsmkv/radtts and the following command:

```
python inference.py -c config.json -r models/model_dap_84000.pt -v hifigan.pt -k hifigan_config.json \
  -t test.txt -s lada --speaker_attributes lada --speaker_text lada -o results
```

## Download

Dropbox link to all models: https://www.dropbox.com/scl/fo/0eoipxgk16o2cnw2ymba3/h?dl=0&rlkey=7trclhuzuo6xno5n06xg4z7gd

### Acknowledgement

- Dmytro Chaplynskyi [@dchaplinsky](https://github.com/dchaplinsky)
- Decoder model for RADTTS++ and Pretrained model for RADTTS++ with DAP config have been trained on the Cluster of Excellence UCU/[Lang-uk](https://github.com/lang-uk).
