# AutoScaling-Using-Heat

    

ScaleUp Policy:
Threshold: 80%

ScaleDown Policy:
Threshold: 5%

Desired Capacity: 1
Max_Size: 3
Min_Size: 1
```bash
    openstack stack create -t template.yaml -e environment.yaml
```


[ⓒ Parth Maniar](https://github.com/officialpm "ⓒ Parth Maniar")

