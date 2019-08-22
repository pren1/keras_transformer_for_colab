# Keras transformer import for colab

Ok, so, since [CyberZHG](https://github.com/CyberZHG) provides the excellent impl of transformer & encoder & decoder, I would like to use it on the Colab. However, it seems that colab only support the tf.keras instead of Keras. So, I just do some modifications to a bunch of libraries provided by CyberZHG, and then the keras transformer could be used in the colab...

You can always do these things by yourself, so I guess you may wanna ignore this repo.

Run the following commands to use these libraries:

```
!git clone https://github.com/pren1/keras_transformer_import.git
mv -v ./keras_transformer_import/* ./
rm -r keras_transformer_import
```

Then, just obtain the get_model func using:

```
from keras_transformer.transformer import get_model
```

That's it!
