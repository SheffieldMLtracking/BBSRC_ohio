# BBSRC_ohio
This is a placeholder repository for the BBSRC project; to allow us to assign tasks.

# Offsets
The colour cameras need their offsets manually determining. This is where I keep a record of these values,

Compute by finding point in colour image, and subtracting location in greyscale image.

| Camera | Box | Offset |
|--------|-----|--------|
|?|1030|26|65|
|?|1031|66|72|
|?|1032|29|37|
|C-DA3075132|1033|-16, -52|
|C-DA3075143|1034|24,48|
|C-DA3063854|1035|-6,89|
|C-DA3063853|1037|22,6|
|?|1039|6,15|

(offset gives how far point in colour image is from the greyscale).

JSON code:
```{"C-DA3075132":[-16, -52],"C-DA3075143":[24,48],"C-DA3063854":[-6,89],"C-DA3063853":[22,6]}```

# Box Status

| Box | to do |
|-----|-------|
|1030 | update btretrodetect; fix offsets |x
|1031 | update btretrodetect; fix offsets |x
|1032 | update btretrodetect; fix offsets |x
|1033 | update btretrodetect; fix offsets |x
|1034 | test |x
|1035 | test |x
|1037 | update btretrodetect; fix offsets |x
|1039 | update btretrodetect; fix offsets |x
|---|---|
|1036 | ? |
|1038 | ? |
|1040 | ? |
