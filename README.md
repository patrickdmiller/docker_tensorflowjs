tensorflowjs

patrickdmiller/tensorflowjs

build

docker build -t patrickdmiller/tensorflowjs .

usage

docker run -it --rm -v `pwd`/tf/:/tf/ patrickdmiller/tensorflowjs:latest tensorflowjs_converter --input_format=keras --output_format=tfjs_layers_model /tf/data/model_classify_no_reset_after.h5 /tf/jsmodel/ 