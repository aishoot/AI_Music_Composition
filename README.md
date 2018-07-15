# AI Music Composition
<img width="75%" height="75%" src="ai-compose-music.jpg"/>

## Dependency Library Installation
Before following instructions, make sure that you have installed Anaconda(Python 3.5+) and [bazel](https://docs.bazel.build/versions/master/getting-started.html) if you want to generate music with [Google's Magenta](https://magenta.tensorflow.org/).
```bash
curl https://raw.githubusercontent.com/tensorflow/magenta/master/magenta/tools/magenta-install.sh > /tmp/magenta-install.sh
bash /tmp/magenta-install.sh
source activate magenta
pip install tensorflow-gpu==1.4.0
pip install magenta-gpu==0.3.2
```
If you want to compose music without Magenta, ignore above steps. But you should run the following command.
```
pip install -r requirements.txt
```


## References
* http://www.cnblogs.com/learn-to-rock/p/5677458.html
* https://www.cnblogs.com/Vito-Yan/p/9032789.html
* https://www.cnblogs.com/charlotte77/p/5664523.html
* https://www.cnblogs.com/lyrichu/p/9006854.html
* [Music and text generation](https://towardsdatascience.com/deep-learning-with-tensorflow-part-3-music-and-text-generation-8a3fbfdc5e9b)
* [How to Generate Music using a LSTM Neural Network in Keras](https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5)
* [Google's Magenta](https://github.com/tensorflow/magenta)
* https://blog.csdn.net/bestbuild/article/details/51927007

*More code will be uploaded soon!*
