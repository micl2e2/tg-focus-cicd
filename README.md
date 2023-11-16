
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


# Artifacts

`docker.io/micl2e2/tg-focus-cicd-toolc:gcc12-deb10-x64`:
- sha256:df4662dc5869ca8575f6fd576ecb8dab7ab6f79dcb94c35968afb1abbc749f54
- https://github.com/micl2e2/tg-focus-cicd/actions/runs/6886233121


