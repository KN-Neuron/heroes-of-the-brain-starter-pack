For linux
```bash
python3 -m venv venv
source venv/bin/activate
pip install ./BrainAccessSDK-linux/python_api
```

```bash
pip install brainaccess
```

OR if you're a windows user

```bash
pip install ./BrainAccessSDK-windows/python_api
```

then

```bash
python3 test.py
```

> there may be slight connectivity issues. Try rebooting the device after few failed attempts.


for signal processing we recommend [MNE](https://mne.tools/stable/index.html) library.
