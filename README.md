# MapChannel2PMT

```console
python map_to_hole.py table.csv
```

The original table must contain columns ```RunNumber``` and ```ChannelID```.

The script uses the tables:

- ProfileStartRun.csv to obtain the profile corresponding to each run in the given table
- HolesMapping.csv to obtain the map of channels to PMTs in each profile
