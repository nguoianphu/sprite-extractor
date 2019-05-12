# sprite-extractor

> Tool for extracting sprites from TexturePacker Spritesheets

Extract sprites from spritesheets created with TexturePacker. Currently only support json hash.

**TODO**

Support more data formats from TexturePacker

## Usage

```
sprite-extractor --sheet input.png --data input.json
```

## Install
```
npm install -g sprite-extractor
```

## Install GraphicsMagick or ImageMagick
```
sudo add-apt-repository ppa:dhor/myway
sudo apt-get update
sudo apt-get install graphicsmagick
sudo apt-get install imagemagick
```

## Change log

**0.0.2**

    * Bug fixes
        * Fix sprite's background is white while it should be transparent

**0.0.1**

    * Initial commit
