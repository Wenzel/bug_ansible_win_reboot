# bug_packer_ansible

## Build

    virtualenv venv
    source venv/bin/activate
    (venv) pip install -r requirements.txt
    (venv) ./packer build windows_10.json

The build should hang on `win_reboot` module
