# Diskless OceanParcels

Run [OceanParcels](https://oceanparcels.org) in diskless mode by streaming velocity data out of a REDIS store and by streaming trajectory data into a REDIS store.

## Example notebook

Here's a static [notebook](parcels/notebooks/2023-02-03_first_steps.ipynb) showing what we have in mind.

## Playing with the setup

Run
```shell
$ docker-compose down && docker-compose build && docker-compose up
```
and connect to https://127.0.0.1:8888 using "oceanparcels" as password for Jupyter.

Details on the setup are in the [`docker-compose.yaml`](docker-compose.yaml).