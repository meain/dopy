# Dopy

Give `filetype`, `link` and `location` in a plain text file. It will download them and put them into the current folder

> If given location is not available, it will create and then copy it over.

## Usage

Create a simple text file like (sample.dopy) and pass that to dopy and it will do its work.

```bash
./dopy sample.dopy
```

## Sample

```
file https://transfer.sh/fakelink/hello.txt ~/Documents/Projects/fakepath
zip https://storage.googleapis.com/models_data/pavada ../somepath
```


## Formats supported

- `file`: any file, simple download
- `zip`: zip files
- `zipi`: unzips and puts files in the folder in the zip to location
