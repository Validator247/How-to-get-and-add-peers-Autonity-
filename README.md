# How-to-get-and-add-peers-Autonity-

    curl -X POST --data '{"jsonrpc":"2.0","method":"admin_peers","params":[],"id":1}' -H "Content-Type: application/json" http://127.0.0.1:8545

Next

    autonity attach http://127.0.0.1:8545


Next

    admin.addPeer("enode://2ea646d4fda624402071facb0d8ef909bf5d98563a8fcff4f026c8ddd75be62a31cad30199a6ff04767108a71a54e492157a3ee03a31b76419b70854b64e5afd@103.219.168.153:30303")
    admin.addPeer("enode://a6cbfd2b20083a90239e5cc4802f70ad51a3a725e3c9727a11542adce71015ad978b0353fc92251fb929e3e892ede756843160d606e4194c97ecedf95467c0b0@205.209.117.146:39160")
    admin.addPeer("enode://68a20105be2a965b406086a6008d16b7bfbac98dde2f541b018a483e20ce529fb5974543cdfaf6045023f1fa6d5c161009d901faf91566cf23470280d0ba9ee8@218.155.161.169:45378")
    admin.addPeer("enode://4bca81e3ff5affaa8e5b9fc823834911e69a2ce511df2976d67a87a44aace67551dce67f69867c94f168559fe6295e1d04d32587d4ddc83dd9135f5be4577f8a@173.249.26.57:30303")


Replace the peer address with the actual address found when used in step 1
