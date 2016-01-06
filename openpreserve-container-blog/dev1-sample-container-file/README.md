## Sample File for Open Preserve Blog on Container Identification
---

The container created is a zip file. Within that two folders and two files. 

The structure is as follows:

    ZIP: dev1-sample-container-format.opf
        |
        |
        +--+ DIR: path-to-find-one\
        |
        |
        +--+ DIR: path-to-find-two\
        |      +
        |      |
        |      |
        |      +--+ FILE: file-to-read-two
        |
        |
        +--+ FILE: file-to-read-one

### Identifying the files inside the container

- The contents of file-to-read-two, expressed as PRONOM regex are: DE C0 DE F1 1E {9} DA 7A
- The contents of file-to-read-one, expressed as PRONOM regex are: DE C0 DE F1 1E
