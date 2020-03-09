Download assets from https://drive.google.com/open?id=1b8-qXr4XkiloCWVqjVsCj8D7QO9pBntr     

Ensure that assets.tar.gz is in the MAX-Audio-Classifier directory     

```

docker build -t max-audio-classifier .

docker run -it -p 5000:5000 max-audio-classifier
```