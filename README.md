
# to download data

```bash
curl --remote-name-all https://repository.clarin.is/repository/xmlui/bitstream/handle/20.500.12537/330{/alignments_json.zip,/alignments_textgrid.zip,/rosa.zip,/salka.zip,/bui.zip,/steinn.zip,/dilja.zip,/ugla.zip,/bjartur.zip,/alfur.zip,/README.md,/LESIST.md}
```

if troubles with training,

```bash
pip install torch==2.3.1 torchaudio==2.3.1 torchvision==0.18.1 in your venv and see if that solves it for you.
```