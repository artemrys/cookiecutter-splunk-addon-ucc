# cookiecutter-splunk-addon-ucc

## Rationale

I need sometimes to create a simple version of the add-on to test or demo smoething. This makes it easy to bootstrap a new add-on without a need to remember all the required files, fields and values.

## How to use

```
python3 -m venv .venv
source .venv/bin/activate
pip install cookiecutter
cookiecutter gh:artemrys/cookiecutter-splunk-addon-ucc
# Enter required values
# You will see a new folder in the root directory that is the new add-on
```

## Example

Checkout this [repository](https://github.com/artemrys/cookiecutter-splunk-addon-ucc-demo) to see an example.
