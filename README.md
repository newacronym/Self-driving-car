# Self-driving-car
a real word self driving car mini model , using raspberry pi and arduino.

 # STEPS TO FOLLOW :
1. install vnc viewer on your pc , it is used to run raspberry pi on system. 
   SETTING VNC-
    a. connect your raspberry pi and your desktop through common network (can be done using mobile hotspot , but remove the password)
    b. setup the raspberry pi , ie systems you need , which can be found in the pdf 'setting raspberrypi'
2.after you are able to open raspberry pi os on your computer , continue , further codes in raspberry pi.
3. first of all run the codes of 'collecting_data' , make sure your locations are valid. this code will collect data as you move your bot from keyboard and stores images to its respective functions , for eg. if you press left button it will store the corresponding image in that 'left' folder.
4. after ruuning 'collecting data' you have now folders which contains image with their repective properties(motion). 
5. upload these folders in google drive .
6. open google collab , run the "training" code in collab , run respective parts. it can take several minutes sometimes and hour or half depending upon the no. of images you have taken.
7. after successfully training your data , you will get a file named as "output.h4" save it in your downloads folder. it is your trained data.
8. now you have trained file , so run the "runnning" code , make sure your address of training file is ok. and also your order is same as used during training.
Enjoy your self driving car.
you can also add extra features ,like recognition of road sign and symbols, your imagination is your limit now.
