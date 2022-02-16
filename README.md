# darpa_tc3_convert

Transfer darpa TC3 json data into ATLAS input format ("Subject Type Object")

1. Download data from DARPA TC3: [google drive](https://drive.google.com/drive/folders/1QlbUFWAGq3Hpl8wVdzOdIoZLFxkII4EK)
2. Create 'data/' folder, put darpa .json data into 'data/' folder
3. Rename the data into the format 'convert.py' can read (ex: 'cadets-e3-0.json' ,'cadets-e3-1.json' ,'cadets-e3-2.json')

4. Run script example:
```
python convert.py --source="data/" --system="cadets" --format="json" --save="cadet-results"
```

