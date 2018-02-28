## Test Transfer Learning

### Get flower photos
```
cd ~
curl -O http://download.tensorflow.org/example_images/flower_photos.tgz
tar xzf flower_photos.tgz
```

### Retrain model

```
python retrain.py --architecture='inception_v3' --image_dir='./flower_photos'
```