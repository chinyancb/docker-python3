# docker-python3

## bulid
$ docker-compose up -d --build

## if you use jupyter notebook
$ docker run -v $PWD/var:/root/var -w /root/src -it --rm -p 7777:8888 <YOUR REPOSITORY> jupyter-lab --ip 0.0.0.0 --allow-root -b localhost
  
access localhost:7777, and login on token
