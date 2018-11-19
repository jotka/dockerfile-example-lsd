# dockerfile-example-lsd
Dockerfile example for LSD



  oc new-app https://github.com/jotka/dockerfile-example-lsd.git

  oc logs -f bc/dockerfile-example-lsd

  oc get services

  oc expose svc/dockerfile-example-lsd

http://dockerfile-example-lsd-myproject.127.0.0.1.nip.io
