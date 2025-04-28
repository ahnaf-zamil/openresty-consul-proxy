# Dynamic Load Balancing Gateway using OpenResty (Nginx + LuaJIT) and Consul

The setup makes use of an OpenResty reverse proxy making DNS queries to Consul to discover healthy service instances at runtime. It routes traffic without needing a static upstream list or a full service mesh.

It's a simple yet effective approach for service discovery and load balancing at the edge, useful when you want dynamic behavior without heavy infrastructure overhead.

![](https://media.discordapp.net/attachments/961613143610638366/1366412990081011732/0_LddLl_o5LISbSTWB.webp?ex=6810dac3&is=680f8943&hm=b34915783a3d89470b5b105c4bc1a9db1d2bef648cc36e8f5ca713a980209409&=&format=webp)
