---
layout: default
title: Configuration with YAML
nav_order: 6
---
# Configuration with YAML

The entire configuration of the wiki can be done with environment variables but also through the file 
`wikmd-config.yaml`.

Please, notice that if you set up both environment variables and `wikmd-config.yaml`, the environment variables take 
precedence.

## Configuration parameters

```yaml
wikmd_host: "0.0.0.0"
wikmd_port: 5000
wikmd_logging: 1
wikmd_logging_file: "wikmd.log"

git_user: "wikmd"
git_email: "wikmd@no-mail.com"

main_branch_name: "main"
sync_with_remote: 0
remote_url: ""

wiki_directory: "wiki"
images_route: "img"
homepage: "homepage.md"
homepage_title: "homepage"

protect_edit_by_password: 0
password_in_sha_256: "0E9C700FAB2D5B03B0581D080E74A2D7428758FC82BD423824C6C11D6A7F155E" #ps: wikmd

local_mode: false
```

Please, refer to [environment variables](environment%20variables.md) for further parameters explanation.