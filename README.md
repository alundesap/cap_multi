capm Application

Build Command:
```
cd cap_multi ; mkdir -p mta_archives ; mbt build -p=cf -t=mta_archives --mtar=cap_multi.mtar
```

Deploy Command:
```
cf deploy mta_archives/cap_multi.mtar -f
```

Undeploy Command:
```
cf undeploy capm -f --delete-services
```
