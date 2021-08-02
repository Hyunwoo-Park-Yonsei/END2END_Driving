# END-TO-END self-driving using raspberry pi

![ex_screenshot1](./img/1.png)


## Final video
[![END2END](http://img.youtube.com/vi/RroL84zUFFQ/0.jpg)](https://www.youtube.com/watch?v=RroL84zUFFQ)

## Procedure

### Making training data

* Made image scale of 48x32 using raspberry pi camera. 

![ex_screenshot2](./DATA/120W.jpg)![ex_screenshot2](./DATA/155D.jpg)![ex_screenshot2](./DATA/206W.jpg)![ex_screenshot2](./DATA/301W.jpg)![ex_screenshot2](./DATA/607W.jpg)![ex_screenshot2](./DATA/8002A.jpg)![ex_screenshot2](./DATA/1203W.jpg)![ex_screenshot2](./DATA/4003W.jpg)![ex_screenshot2](./DATA/5404D.jpg)


### Training model

* Made image gray to scale down the data and the model.
* Used CNN to train the model.

![ex_screenshot2](./img/2.png)

### Streming the data to the raspberry pi

* I've tried to use the model to decide direction but the model was too heavy for Pi to run it.
* So I decided to receive the camera image from the Pi to my laptop and run the model in my laptop then send the decision to the Pi.
* It has reduced the decision making time 1/10 from 0.3s to 0.03s.





