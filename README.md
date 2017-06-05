# Packer Docker Container

Official Packer images have preconfigured Entrypoint, which could be problematic for some use-cases, where it's not possible to overwrite it. For example, Gitlab CI explicitly set command to run `sh` first and only then execute user-provided scripts.
