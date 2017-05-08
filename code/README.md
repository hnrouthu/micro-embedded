Usage
--------------------
To compile the code use the below<br>
g++ main.c test_client.h facerec_video.hpp SparkFun_APDS9960.cpp SparkFun_APDS9960.h temp.c i2c-dev.h i2c-id.h i2c.h ProxSensorCamTemp.hpp gpio-galileo.h -lcurl -lpthread `pkg-config --cflags opencv` `pkg-config --libs opencv`

While execution input numbers as instructed in thread 0.
Make sure that the temperature value exceeds 26 or proximity value exceeds 150 to trigger the sending of image to the webserver.

We are using images from AT&T Database of Faces for training in face recognition.<br>
http://www.cl.cam.ac.uk/research/dtg/attarchive/pub/data/att_faces.zip
