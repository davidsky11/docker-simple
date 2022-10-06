# docker-simple
Dockerfile compose test


Docker daemon configuration file: 
```bash
{
  "builder": {
    "gc": {
      "defaultKeepStorage": "20GB",
      "enabled": true
    }
  },
  "experimental": false,
  "features": {
    "buildkit": true
  },
  "registry-mirrors": [
    "https://md4nbj2f.mirror.aliyuncs.com"
  ]
}
```