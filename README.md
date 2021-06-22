# MembraneRemoteStreamFormat

Use while `membrane_core` is `0.7.0`, but lots of plugins still assume they are using
`0.6.x`, and need to pull in `membrane_remote_stream_format` as a separate package.

```
{:membrane_remote_stream_format, path: "sax/fake_membrane_remote_stream", override: true},
```

