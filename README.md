<!-- # 🪙 Token -->

[//]: # '<img alt="workshop/token" width="1412" src="../.resources/token.png">'

# Vibe With Dr. Adaku

### The Second Task From The Workshop

Leo is a functional, statically typed programming language built for writing private applications. Leo is a high-level programming language that compiles down to low-level Aleo Instructions.

I changed the transfer function input in the `token.in` file.

I added this:

```
[transfer_private]
sender: token = token {
  owner: aleo19pu64fuk0pgmkxzl2s8mwz9dcex6g4tdh4pmehd9fh9wdz9xdcgshprdr4,
  amount: 10u64,
  _nonce: 710947497959521588541978475371274797290179560223644761302029085270296751312group
};

receiver: address = aleo14f6r8ee728arw8u2mgqfv37xk7lputxk5yman56krp2gn84a8urqfwnkkf;
amount: u64 = 3u64;
```

Used the command:

```
leo run transfer_private
```

I also changed the private key in the env file.

---

A transparent & shielded custom token in Leo.

## Run Guide

To run this program, run:

```bash
./run.sh
```
