# how to set up
- First it requires to install CAEN software libs: https://www.caen.it/subfamilies/software-libraries/
- We need CAENVMElib, CAENCommLib, CAEN HV Wrapper lib
- Python wrapper is available: https://github.com/caenspa/py-caen-libs
- Doc for CAEN HV wrapper: https://www.caen.it/products/caen-hv-wrapper-library/

# how to run  CAENHV.py
```
python3 CAENHV.py
```

# how to run demo code:
```
python3 demo_hvwrapper.py -s SY4527 -l TCPIP -a 192.168.0.1
python3 Taotest_hvwrapper.py -s SY4527 -l TCPIP -a 192.168.0.1
```
