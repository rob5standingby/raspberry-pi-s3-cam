# Raspberry Pi Camera Amazon S3 Uploader

## Requirements
- Raspberry Pi + Camera + Network Adapter

## Initial Setup
- Ensure Raspberry Pi Camera has been enabled:
  - Running `sudo raspi-config` will get you into the settings to enable

- Install the `python-picamera` library:
  ```
  sudo apt-get update
  sudo apt-get install python-picamera
  ```

- Install `tinys3` library: `pip install tinys3`
- Install `pyyaml` library: `pip install pyyaml`
- Update `config.yml` and provide S3 credentials as well as specify a bucket name

## Running 
`python s3cam.py`
