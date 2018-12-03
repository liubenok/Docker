Thumbor Docker image with MozJPEG
====

Extend from https://github.com/APSL/docker-thumbor

Example usage
----
`docker run -e DETECTORS="['thumbor.detectors.face_detector','thumbor.detectors.feature_detector']" -p 8000:8000 dictcp/thumbor`

