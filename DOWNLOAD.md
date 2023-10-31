Dataset **ROAD-SEC** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/q/X/Wo/ow5VL7vtk3Yma4jYGuoqzrLr3Q51qxQVSbdVMy3YtzKGqjjtkwD6uEKmJzdBoCVJSMw1HCv722wSM6dN3eHtBhgrAFk08ZvzJF1zS2jezmHsNXO7BjJ4rwaJ9cBg.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='ROAD-SEC', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

