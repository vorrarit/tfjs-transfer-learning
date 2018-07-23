git clone https://github.com/tensorflow/tfjs-converter
cd tfjs-converter
git checkout v0.5.2

python tfjs-converter\python\tensorflowjs\converters\converter.py --input_format keras --output_format tensorflowjs .\h5\mobilenet_2_5_224_tf.h5 .\model