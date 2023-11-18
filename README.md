
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
- id: 3dc5511482c72deb026884e955cb9063d15973217200a1b28a003e43cdb55dee
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6886233121

`docker.io/micl2e2/tg-focus-cicd-tdlib:030e440757478ef5f5fdb01f60c3c6d885330c72-gcc12-deb10-x64`:
- id: d158c48baa7091637da9bb383a51b5e1ad14b755f2c7a5a1f4f48160c50f7c44
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6887318188
- corresponding tdlib version: 1.8.14

`docker.io/micl2e2/tg-focus-cicd-tdlib:030e440757478ef5f5fdb01f60c3c6d885330c72-default-alp318-x64`:
- id: 7d7758d7afcdf4e7dd491b5cac96452a33c8d05410b05159a87dcedda62be298
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6892528556
- corresponding tdlib version: 1.8.14

`docker.io/micl2e2/tg-focus:1.4.1814-x64-linux-musl`
- id: 7acea365b23975c2cdb1ceed3a46dd8977cc36609ae2bbce0eba3494c19d5b48
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6899217558

`tg-focus-1.4.1814-x64-linux-gnu`
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6888621611

`docker.io/micl2e2/tg-focus-cicd-tdlib:ec788c7505c4f2b31b59743d2f4f97d6fdcba451-gcc12-deb10-x64`
- id: ec4c47c38b820bf0596268dc15c8acef68c8bab06a6a36b3e2e508a5fb097161
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6911157079
- corresponding tdlib version: 1.8.21

`docker.io/micl2e2/tg-focus-cicd-tdlib:ec788c7505c4f2b31b59743d2f4f97d6fdcba451-default-alp318-x64`
- id: 42e063e7dbb26ef3871f3fbca936d00ed2ee64712c6a466226099b00a2a86b7d
- artifacts: https://github.com/micl2e2/tg-focus-cicd/actions/runs/6912676245
- corresponding tdlib version: 1.8.21
