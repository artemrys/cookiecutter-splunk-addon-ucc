# {{cookiecutter.addon_name}}

## To run locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install splunk-add-on-ucc-framework
pip install splunk-packaging-toolkit
ucc-gen --ta-version=0.0.1
slim package output/{{cookiecutter.addon_name}}
```

Then you will see an archive in the root directory which you can install through Splunk UI.
