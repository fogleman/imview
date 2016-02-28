# imview

Simple image viewer written in Go + OpenGL.

## Installation

    go get -u github.com/fogleman/imview/cmd/imview

## Usage

    imview first.jpg second.png third.bmp

## API

You can show a single image...

```go
var image *image.RGBA
// ...
imview.Show(image)
```

Or multiple images, each in their own window...

```go
var images []*image.RGBA
// ...
imview.Show(images...)
```
