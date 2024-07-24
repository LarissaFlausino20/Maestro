# Maestro 🎹

Maestro is the easiest way to automate UI testing for your mobile app.

> **Note**
> **Full documentation for Maestro can be found at [maestro.mobile.dev](https://maestro.mobile.dev)**


<img src="https://user-images.githubusercontent.com/847683/187275009-ddbdf963-ce1d-4e07-ac08-b10f145e8894.gif" />



# Maestro samples

`maestro download-samples` provides a set of flows and apps so that users can quickly set up a maestro test, without having to create an app.

download-samples downloads these files and apps from storage.googleapis.com.

# Update the samples

Although the samples are checked in, updating them requires a few manual steps:

* Change the samples in this directory and merge these changes
* Run `maestro download-samples`
* Copy *.yaml to the samples directory created by download-samples
* Run `(cd samples && zip -r "$OLDPWD/samples.zip" . -x "/**/.*" -x "__MACOSX")`
* Open https://console.cloud.google.com/storage/browser/mobile.dev/samples
* Upload samples.zip
* Adjust the permissions of samples.zip to "Public to Internet"
* Run `maestro download-samples` and verify that the change was successful

## Contatos

<a href="https://www.linkedin.com/in/larissa-flausino-49a942213/">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
     <a href = "mailto:larissaflausino05@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank">
  </a>
