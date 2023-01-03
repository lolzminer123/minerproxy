# submitonlyhighsharesproxy
submit high shares only skip low shares written in python all you need todo is download it extract file, run python3 -m pip install -r requirements.txt then run python3 submit-highshares.py
input your pool address like stratum://k1pool.com port is ur miners port to pool
input ur miner address with worker name thats it and hit run
This is working with latest miner software like gminer , lolminer,nbminer & trex miner
the url and port from the largehash will need to be input into ur gminer in address and port and then the shares will be forwarded to ur pool,
the ping is very low when i tested it it was 12ms 14ms on 2miners depending on what country your from.

works on all windows

please install python 10 upwards not sur if works on python 11 but may do but make sure u install requirements first otherwise proxy will fail

todo

add low share option incase a user wnats low shares solo or both shares solo

tested on

k1pool
2miners

software used

gminer
lolminer
trex miner
nbminer

works with connection to mining rig rentals not sure if good idea 2 proxys running ,
can be edited to run through nicehash if u no how 

todo

clean the code up for alot smoother exprience
inout own gui better display
connect to nicehash or nicehahs through proxy to pool.
