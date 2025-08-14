# influx-ds

a small command line tool to downsample influxdb3 data

## requirements

```bash
pip install pandas influxdb3-python
```

## TIP for token management

```bash
export TOKEN=tokencontenthere
```
and then

```bash
./influxds sandbox bake bake_ds --debug -i 10.105.118.238 -t $TOKEN
```



