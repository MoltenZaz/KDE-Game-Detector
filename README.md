This is a kwin script and a python script that I use to detect games and change my zmk keyboard layer using raw hid.
The helper python script was based on the example video wall script and I also used chatgpt to assist, so probably not the optimal way to do it but it works well enough.
the 99-mykeyboard.rules is a udev rule to map my keyboard so that the hidraw device thing stays static
