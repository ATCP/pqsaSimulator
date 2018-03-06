read adjustGammaTofficer.py and create dir according adjustGammaTofficer.py

top: put bandwidth trace into this dir, e.g., downlink_0 and downlink_1000000
datapath: results dir, the results from bandwidth trace downlink_600000 are put into datapath/downlink_600000
savepath: all the results from datapath are cut and paste into savepath

how to run:

make sure whether result.txt exists, if not exists, it is fine, otherwise, make sure you can understand the results in result.txt
make
python adjustGammaTofficer.py
