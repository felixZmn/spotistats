# spotistats

A helm chart to deploy "Your Spotify", a web app that tracks your Spotify listening history and provides insights on your listening habits.

The app can be found at [https://github.com/Yooooomi/your_spotify](https://github.com/Yooooomi/your_spotify)

## development

```bash
helm package .
helm push spotistats-*.tgz oci://ghcr.io/felixzmn/helm
```
