Dataset **Face Mask Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/X/f/sz/zIzj3H9VrRVr8pwbzaCoNytBgcbmlrV8TXpU2IgqDhAXaqtkGb3ZGFnfNw16DdW7CpOAkis5S3QbKW8jthUKGihGstXWMdcCCpVwoMd5TlIVRUmGBjdLzB7LV7aQ.tar)

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