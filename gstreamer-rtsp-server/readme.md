# Gstreamer RTSP Server
To create an RTSP server run the setup script then run the python script with these commands:

> source venv/bin/activate  
> python3 main.py <rtsp_source>

NOTE: To use the basler source, run the setup with the basler argument (unless basler's already been configured)
> bash setup.sh basler

## Sources
* test: Test-source
* usb_cam: v4l2 source
* basler: basler source