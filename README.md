### sqlite3

```bash
sqlite3 2015_stations.db
```

```sql
.tables
```

```sql
.exit
```

```sql
PRAGMA table_info(stations);
```

```sql
SELECT * FROM stations LIMIT 10;
```

### Linux user groups

Check for group/add user group. Complains if group exists
```bash
sudo groupadd webgroup
```

Add user to group
- The `-a` flag appends the user to the group(s) specified without removing them from other groups.
- The `-G` flag specifies the group(s) to which the user should be added.

```bash
sudo usermod -aG webgroup www-data
```

### ogrinfo

List attributes in shapefile

```bash
ogrinfo -so -al Zumwalt2023.shp
```
