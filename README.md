# s1n3p1.github.io

```python
import folium

map = folium.Map(location = [36, 37], zoom_start = 3)

folium.Marker(
    [7.98421, 98.33086],
    tooltip = 'Phuket',
    popup = folium.Popup('170817~170821'),
).add_to(map)

folium.Marker(
    [33.56864, 130.35804],
    tooltip = 'Fukuoka',
    popup = folium.Popup('180130~180202'),
).add_to(map)

folium.Marker(
    [43.24885, 76.87969],
    tooltip = 'Almaty',
    popup = folium.Popup('180623~180624'),
).add_to(map)

folium.Marker(
    [55.76148, 37.62160],
    tooltip = 'Moscow',
    popup = folium.Popup('180624~180626 180628~180630'),
).add_to(map)

folium.Marker(
    [55.78888, 49.12271],
    tooltip = 'Kazan',
    popup = folium.Popup('180627~180628'),
).add_to(map)

folium.Marker(
    [48.16980, 17.19961],
    tooltip = 'BTS (Bratislava)',
    popup = folium.Popup('180630(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [48.17305, 16.33157],
    tooltip = 'Meidling (Wien)',
    popup = folium.Popup('180630(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [47.37690, 8.54086],
    tooltip = 'Zurich',
    popup = folium.Popup('180701 180703'),
).add_to(map)

folium.Marker(
    [46.68606, 7.86246],
    tooltip = 'Intelaken',
    popup = folium.Popup('180702~180703'),
).add_to(map)

folium.Marker(
    [50.93738, 6.96181],
    tooltip = 'Köln',
    popup = folium.Popup('180704(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [52.36747, 4.90018],
    tooltip = 'Amsterdam',
    popup = folium.Popup('180704~180706 180708~180710'),
).add_to(map)

folium.Marker(
    [50.84889, 4.35803],
    tooltip = 'Brussel',
    popup = folium.Popup('180706~180708'),
).add_to(map)

folium.Marker(
    [48.86934, 2.35240],
    tooltip = 'Paris',
    popup = folium.Popup('180710~180717'),
).add_to(map)

folium.Marker(
    [50.11059, 8.68075],
    tooltip = 'Frankfurt',
    popup = folium.Popup('180717(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [51.24436, 71.43269],
    tooltip = 'Astana',
    popup = folium.Popup('180718'),
).add_to(map)

folium.Marker(
    [35.68055, 139.76887],
    tooltip = 'Tokyo',
    popup = folium.Popup('190122~190126 230429~230501'),
    icon = folium.Icon(color = 'pink', prefix = 'fa', icon = 'heart')
).add_to(map)

folium.Marker(
    [22.44185, 54.65098],
    tooltip = 'AUH (Abu Dhabi)',
    popup = folium.Popup('221201(T) 221204(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [25.28790, 51.53013],
    tooltip = 'Doha',
    popup = folium.Popup('221201~221204'),
).add_to(map)

folium.Marker(
    [37.61917, -122.38210],
    tooltip = 'SFO (San Francisco)',
    popup = folium.Popup('221219(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [38.95057, -77.45025],
    tooltip = 'IAD (Washington D.C.)',
    popup = folium.Popup('221219(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [40.71378, -74.00517],
    tooltip = 'New York',
    popup = folium.Popup('221220~221222'),
).add_to(map)

folium.Marker(
    [28.54130, -81.37866],
    tooltip = 'Orlando',
    popup = folium.Popup('221222~221225'),
).add_to(map)

folium.Marker(
    [32.89975, -97.04035],
    tooltip = 'DFW (Texas)',
    popup = folium.Popup('221225(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)

folium.Marker(
    [34.67145, 135.49828],
    tooltip = 'Osaka',
    popup = folium.Popup('230824~230827'),
).add_to(map)


folium.Marker(
    [14.51256, 121.01649],
    tooltip = 'MNL (Manila)',
    popup = folium.Popup('240117(T) 240121(T)'),
    icon = folium.Icon(color = 'green', prefix = 'fa', icon = 'exchange')
).add_to(map)


folium.Marker(
    [9.84801, 124.14378],
    tooltip = 'Bohol',
    popup = folium.Popup('240116~240121'),
    icon = folium.Icon(color = 'pink', prefix = 'fa', icon = 'heart')
).add_to(map)

map.save('index.html')
```
