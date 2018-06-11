# Conversion to Json Format

##### Import all the packages:
 - Tensorflow , numpy
 - Note : Tensorflow has not yet included all the modules of lite in the recent tensorflow version.


###### You should have a particular frozen graph in the recent directory.


##### Names of the output tensors:

  - Whenever you use the frozen graph we have their output tensors which we need to use them in the Json converter.

 

##### Directory to which we want to convert.

!tensorflowjs_converter --input_format=tf_frozen_model --output_node_names='output_node'  FF_OD_RGB_squeeze_13Oct.pb profile/

Where the profile  is the folder to which we want our saved models.
