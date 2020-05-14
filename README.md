# m3u8_to_vivosx_server
bash script to download m3u8 stream as mp4 file and upload it to vivo.sx

## note that file extentions are optional; m3u8 and mp4 will be set if missing.

### to download/convert and upload
```
./m3u8_to_server -t { api token } \
                 -s { path to m3u8 file } \
                 -f { path to local file to save into and then upload from }
```

### only to download/convert
```
./m3u8_to_server -t { api token } \
                 -s { path to m3u8 file } \
                 --download-only
```

### only to upload
```
./m3u8_to_server -t { api token } \
                 -f { path to local file to upload } \
                 --upload-only
```
