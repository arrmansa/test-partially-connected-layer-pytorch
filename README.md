# test-partially-connected-layer-pytorch <br>
Running some tests on partially connected layers on pytorch <br>
Made a drop in replacement for nn.Linear with Lowlinear <br>
Might test it on some larger networks... might be fun <br>
Results seem to be good on small networks, although it is slightly slow. <br>
Maybe random indexing is a bad idea, but it seems to work at relatively little overhead. <br>
