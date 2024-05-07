# NOAH_MP_v1.1

This is a repo of NOAH-MP model (V1.1). 

Original URL: [https://ral.ucar.edu/sites/default/files/docs//simple-driver-noahmp-v11tar.gz](https://ral.ucar.edu/sites/default/files/docs//simple-driver-noahmp-v11tar.gz)

## Use docker ...

	docker run -it --name noahmp11_2023 --volume=$PWD:/home:delegated --workdir=/home -p 9819:8888 --restart=no --runtime=runc -t -d wk1984/noahmp11_2023