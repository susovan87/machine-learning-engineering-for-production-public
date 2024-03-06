# Machine Learning Engineering for Production

Welcome to the public repo for [deeplearning.ai](https://www.deeplearning.ai/)'s Machine Learning Engineering for Production Specialization.

Here you will find public resources for the courses of this specialization.

## Want to contribute?

At the time being we are not accepting Pull Requests but if you have any suggestion or spot any bug please raise an issue.


## Docker: General purpose
```bash
docker build --rm --tag my-ml-image .
docker run -it --rm -p 8888:8888 -p 8000:8000 --mount type=bind,source="$(pwd)",target=/home/jovyan/work my-ml-image
```

## Docker: TF Extended?
```bash
# Doesn't work
docker run -it --rm -p 8888:8888 -p 8000:8000 --mount type=bind,source="$(pwd)",target=/home/jovyan/work tensorflow/tensorflow:latest-gpu-jupyter
```