Dataset **Face Mask Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/7/K/Oa/pI5VV1gTUY369UnSXosShfQmmLtkUAyNHUmUrVxBnNf6FetlYfR7KlgHkc0EF4sVrFFLpvDQIf0aTr6LGRchQXtIOe1FSK6yQEPzsBG6xF6gXfpfPj25XseuOsd1.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Face Mask Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection/download?datasetVersionNumber=1).