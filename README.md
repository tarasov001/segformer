
### Original repository: [segformer](https://github.com/fajilatun/segformer)

### Requirements
Docker

### Steps to run the solution

Clone the repository:
```bash
$ git clone https://github.com/tarasov001/segformer
$ cd segformer_unn
```

Build and run docker:
```bash
$ docker build -t segmentation -f Dockerfile .
$ docker run segmentation
```

To view images:
```bash
$ docker cp <CONTAINER ID>:segformer/segformer/assets images
```

To find out the CONTAINER ID:
```bash
$ docker ps -a
```
