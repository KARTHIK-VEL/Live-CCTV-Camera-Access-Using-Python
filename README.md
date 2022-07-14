# Live-CCTV-Camera-Access-Using-Python
To Access Live CCTV Camera Using Python
# Environment setup:

1. Install Anaconda:

 https://www.anaconda.com/download/
 
2.Creating an environment with commands

   * To create an environment:
   
           conda create --name myenv
     
     !Note:
     Replace myenv with the environment name.
   
   * When conda asks you to proceed, type y:
   
           proceed ([y]/n)?
           
     This creates the myenv environment in /envs/. No packages will be installed in this environment.

     
       
3. Activating an environment
  
  * To activate an environment:
       
           conda activate myenv
   
   !Note:
Replace myenv with the environment name or or directory path

4. Install Python packages

     * Numpy
     * OpenCV

   Install the required packages by executing the following command.

       pip install (package name)
    
       example:
  
           $ pip install numpy
           
    Make sure pip is linked to Python
    
    Using Python virtual environment is highly recommended.
    
    ## Usage:
    
    webcam
    
    $ Live_CCTV.py
    
    !Note:
          
         * Replace username with the your CCTV username.
         * Replace password with the your CCTV password.
         * Replace IP with the your CCTV IP.
              
                                      
              cap = cv2.VideoCapture('rtsp://username : password @ ip /live')
              
                  eg:
                     cap = cv2.VideoCapture('rtsp://karthik:12345@10.10.20.30/live')
     When you run the script for the first time, it will download the pre-trained model from this link and place it under pre-trained directory in the current path.
    
    ## Help
    
    If you are facing any difficulty, feel free to create a new issue or reach out on [Linkedin](https://www.linkedin.com/in/karthik-v-926656211/)
