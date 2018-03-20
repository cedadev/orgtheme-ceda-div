# orgtheme-ceda-div

Bootstrap 4 organisation theme (colour scheme) for "CEDA Division" web components.

The demo page demo/index.html provides examples of typography, layout styles and functional elements which can be used to construct templates.

It is not, itself, a template.

## Installation

For development purposes, the theme can be installed as follows. For production purposes it should be linked to in-place on the CEDA artefacts server.

`orgtheme-ceda-div` can be installed directly from Github using pip, e.g. into an existing `venv`:

```
$ virtualenv --no-site-packages ./venv
$ source ./venv/bin/activate
$ pip install git+https://github.com/cedadev/orgtheme-ceda-div.git
```
It is intended to be used as a building bock for subsequent framework (e.g. Django) and application (e.g. catalogue service)