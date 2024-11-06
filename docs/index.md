# AI Software Template

This application, finally, is created from an AI Software Template. These software templates create a new source code repository as well as a new GitOps deployment repository.

The chosen sample source applicable is included in the source code repository.

## Sample Source Application

An AI-enabled audio transcription streamlit application. Upload an audio file to be transcribed.

## Repositories

The source code for your application can be found in [https://github.com/jrichter-rhtap/finalaudio ](https://github.com/jrichter-rhtap/finalaudio ).
 
The GitOps repository, which contains the Kubernetes manifests for the application can be found in 
[https://github.com/jrichter-rhtap/finalaudio-gitops ](https://github.com/jrichter-rhtap/finalaudio-gitops ). 

## Application namespaces 

The default application is found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.