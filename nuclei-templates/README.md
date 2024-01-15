## Usage

To be used with nuclei https://github.com/projectdiscovery/nuclei

To scan a list of target URLs:

`nuclei -l urls -t template.yaml`

To scan a single target:

`nuclei -u https://<target> -t template.yaml`

