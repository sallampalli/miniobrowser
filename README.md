y# Minio File Browser

``miniobrowser`` provides minimal set of UI to manage buckets and objects on ``minio`` server. ``miniobrowser`` is written in javascript and released under [Apache 2.0 License](./LICENSE).

## Installation

```sh
$ git clone https://github.com/minio/miniobrowser
$ cd miniobrowser
$ curl -o- -L https://yarnpkg.com/install.sh | bash
$ yarn
```

### Install `go-bindata` and `go-bindata-assetfs`.

If you do not have a working Golang environment, please follow [Install Golang](https://docs.minio.io/docs/how-to-install-golang)

```sh
$ go get github.com/jteeuwen/go-bindata/...
$ go get github.com/elazarl/go-bindata-assetfs/...
```

## Generating Assets.

### Development version

```sh
$ yarn build
```

### Released version

```sh
$ yarn release
```

## Run Minio File Browser with live reload.

```sh
$ yarn dev
```

Open [http://localhost:8080/minio/](http://localhost:8080/minio/) in your browser to play with the application
