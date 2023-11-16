
# Image Dependency Relationship:

target `x64-linux-gnu`:

`tg-focus-cicd-toolc:gcc12-deb10-x64` depends on:
- `debian:buster-slim`

`tg-focus-cicd-tdlib:GITCMM-gcc12-deb10-x64` depends on:
- `debian:buster-slim`
- `tg-focus-cicd-toolc:gcc12-deb10-x64`

`tg-focus:GITTAG-x64-linux-gnu` depends on:
- `debian:buster-slim`
- `tg-focus-cicd-tdlib:GITCMM-gcc12-deb10-x64`

target `x64-linux-musl`:

`tg-focus-cicd-toolc:default-alp318-x64` depends on:
- `alpine:3.18`

`tg-focus-cicd-tdlib:GITCMM-default-alp318-x64` depends on:
- `alpine:3.18`
- `tg-focus-cicd-toolc:default-alp318-x64`

`tg-focus:GITTAG-x64-linux-musl` depends on:
- `alpine:3.18`
- `tg-focus-cicd-tdlib:GITCMM-default-alp318-x64`
