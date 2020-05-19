# sqlplu

## confirm sqlplus version
```
$ sqlplus -v
```

## export as csv

```
$ sqlplus -m 'csv on quote on' -s -l tiger/scott @./toaru-query.sql | tee /dev/tty | tail -n +2 | gzip -c >./toaru-result.csv.gz
```

