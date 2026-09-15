# CSC5002 Micro-project

N.B.: please, conform to the MarkDown format: See 

## Getting started

If you want a copy of the skeleton before starting programming, we
suggest that you copy the `MiniSocs` directory, e.g. into
`MiniSocs-skeleton`:

```
# copy
$ cp -r MiniSocs MiniSocs-skeleton
# git version management
$ git add MiniSocs-skeleton
$ git commit -m "copy of the skeleton before starting programming"
$ git push origin main
```

If you also want to browse in the same IDE (we favor Eclipse) the two
versions, we suggest that you change the artefats identifiers in the
Maven `pom.xml` files:

```
# list all the files to modify
$ find MiniSocs-skeleton/ -name "pom.xml"
MiniSocs-skeleton/minisocs-frontend/startup/pom.xml
MiniSocs-skeleton/minisocs-frontend/hexagon/pom.xml
MiniSocs-skeleton/minisocs-frontend/pom.xml
MiniSocs-skeleton/minisocs-frontend/common-api/pom.xml
MiniSocs-skeleton/pom.xml
# change artefactId in pom.xml (we favor emacs)
$ find MiniSocs/ -name "pom.xml" -exec emacs {} \;
# replace every occurrence of '<artifactId>minisocs-' by '<artifactId>minisocs-skeleton-'
```

Before launching your IDE (we favor Eclipse), we suggest that you build
the software:

```
# The first execution of the following command may take some time:
# This is due to the download of many JAR archives in your local Maven
# repository ~/.m2/repository
$ mvn clean install
```

Now, start programming: opening the IDE, etc. with the MiniSocs
Frontend microservice in directory `MiniSocs/minisocs-frontend/`: See
the [`readme.md`](./MiniSocs/minisocs-frontend/readme.md) file with
the presentation of the MiniSocs application.


## Comments and Status of the project

Teachers' note: In this section, you write the comments for the review
and the evaluation of your work. For instance, you detail precisely
the status of project, i.e. your progress on the project in the form
of a task list (as proposed in the Labs).

TODO
