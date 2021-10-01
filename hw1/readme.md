 

* 目的 建置link

$ bazel run onos-local – clean debug

* onos
onos localhost
onos: activate org.onosproject.fwd


* mininet
sudo mn --custom=project1_part2_309551111.py --topo=topo_part2_309551111 --controller=remote,ip=127.0.0.1:6653
pingall
dump

sudo mn --custom=project1_part3_309551111.py --topo=topo_part3_309551111 --controller=remote,ip=127.0.0.1:6653
