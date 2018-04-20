# packet_replication
Packet replication using refcnt_update and memcpy in dpdk

# How to make
run "make" in ipv4_memcpy or ipv4_refcnt repository.

# How to run
./build/ipv4_refcnt -c 0x00f -n 3 -- -p 0xf -q 1

./build/ipv4_memcpy -c 0x00f -n 3 -- -p 0xf -q 1

or 

for help - ./build/ipv4_refcnt -h
