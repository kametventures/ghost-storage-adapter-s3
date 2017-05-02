# Ghost storage adapter S3

An AWS S3 storage adapter for Ghost 1.0+

## Installation

```
yarn add git+ssh://git@github.com:kametventures/ghost-storage-adapter-s3
mkdir -p ./content/storage
cp -r ./node_modules/ghost-storage-adapter-s3 ./content/storage/s3
```

## Configuration

```
storage: {
  "active": {
    "images": "s3"
  },
  s3: {
    accessKeyId: 'YOUR_ACCESS_KEY_ID',
    assetHost: 'YOUR_OPTIONAL_CDN_URL',
    bucket: 'YOUR_BUCKET_NAME',
    pathPrefix: 'YOUR_OPTIONAL_BUCKET_SUBDIRECTORY',
    region: 'YOUR_REGION_SLUG',
    secretAccessKey: 'YOUR_SECRET_ACCESS_KEY'
  }
}
```

## Support

This library works with Ghost 1.0

## License

[ISC](./LICENSE.md).
