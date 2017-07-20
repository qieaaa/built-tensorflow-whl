Introduction
----
This responsity is about TensorFlow linux installation, I built them from TensorFlow source with CUDA8.0 and specially with `cuDNN6.0` which is more effecient than version of 5.0.
I carefully follow the instruction of [offical guide](https://www.tensorflow.org/install/install_sources)<br>
I tried all these on my own pc, it works well~<br>

PS
There may be an error `ImportError: /home/hzy/anaconda3/bin/../lib/libstdc++.so.6: version 'CXXABI_1.3.8'` not found <br>
you can solve it by<br>
`cp /usr/lib/x86_64-linux-gnu/libstdc++.so.6 /home/jj/anaconda2/bin/../lib/libstdc++.so.6`



TODO
----
add more python versions
