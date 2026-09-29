# Flower8 releases

Android downloads for **Flower8**, a private app for couples: live map, chat,
a pet you raise together, shared notes, drawing and games for two.

This repository holds only the release APKs, not code. The app checks it
for new versions, and once Flower8 is installed you can update it from
inside the app: **Profile → About → App version**.

## Install

1. Open the [latest release](https://github.com/lestorrr/flower8-releases/releases/latest)
   on your phone and download the `.apk`.
2. Open it. Android asks once to allow installs from your browser or file
   manager. Allow it, then tap **Install**.

An update installs over the version you have: your account, chats and
settings stay.

## Is this the real Flower8?

Every release is signed with the same key. Android refuses an update signed
with any other key, so a changed APK can never replace the app you have.
To check a download yourself, its signing certificate must match:

```
CN=Lester Liclican, O=Flower8, L=Bulacan, C=PH
SHA-256: c7:71:f8:9e:f9:81:a4:37:ae:5e:6c:26:7c:a9:9d:2f:52:9b:0e:b8:17:af:90:ae:a6:71:65:93:73:8b:80:ce
```

## Privacy and contact

- Privacy policy: https://flower8-backend.onrender.com/privacy
- Contact: lesterliclican22@gmail.com

Made by Lester Liclican, Bulacan, Philippines.
