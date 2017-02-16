# UbuntuScripts
This repository will be used to give a guideline solution for most of known issues with ubuntu.

## How to avoid transparent_hugepage/defrag warning from mongodb

If you receiving the folowing warning from mongodb about THP, then you get you cen the solution for this issue from disable-transparent_hugepages script.

2015-03-06T21:01:15.526-0800 I CONTROL  [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/defrag is 'always'.
2015-03-06T21:01:15.526-0800 I CONTROL  [initandlisten] **        We suggest setting it to 'never'

