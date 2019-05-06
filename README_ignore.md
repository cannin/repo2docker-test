Removing intermediate container f580dc8d0e3b
 ---> 9cb80931b407
Step 54/62 : LABEL repo2docker.version="0.8.0+158.g9099def.dirty"
 ---> Running in aad838715de7
Removing intermediate container aad838715de7
 ---> 1446612ea644
Step 55/62 : LABEL repo2docker.repo="https://github.com/cannin/repo2docker-test"
 ---> Running in a1f3f8dd31be
Removing intermediate container a1f3f8dd31be
 ---> 917e63e65127
Step 56/62 : LABEL repo2docker.ref="eb72aca38962353c5c285e99645ce7433b0b8829"
 ---> Running in d451951a15c0
Removing intermediate container d451951a15c0
 ---> 358c8768ed5f
Step 57/62 : USER ${NB_USER}
 ---> Running in e98514531993
Removing intermediate container e98514531993
 ---> 77c61b3bd92d
Step 58/62 : RUN chmod +x postBuild
 ---> Running in db50bf542944
Removing intermediate container db50bf542944
 ---> d8f266fc3b1b
Step 59/62 : RUN ./postBuild
 ---> Running in c40c3bb5c5e4

https://mybinder.org/v2/gh/cannin/repo2docker-test/master?urlpath=rstudio

Successfully pushed gcr.io/binder-prod/r2d-f18835fd-cannin-2drepo2docker-2dtest-10ad1c:eb72aca38962353c5c285e99645ce7433b0b8829Built image, launching...

NRNB Outreach Jupyter Notebook Related

I spent some time today away from the writing and got this working:

https://mybinder.org/v2/gh/cannin/repo2docker-test/master?urlpath=rstudio

This is a very flexible idea for temporary environments for many languages (i.e., R, Python, Julia) that can either be Jupyter notebooks or even better for R can be RStudio. Even better than this it seems to a very configurable environment unlike Microsoft Azure or Google Colaboratory. The notebook above has rJava installed testable with: source("main.R")


https://mybinder.org/v2/gh/cannin/network-analysis-tutorials/master?urlpath=rstudio

I hope you had a good trip.
