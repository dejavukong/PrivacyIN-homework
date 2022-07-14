# Suvi-susu#8206-None-[zkSNARKs Application Survey]

## 基于zk-snark构建的应用

### 链

- loopring- zkRollup-based layer2 DEX: https://github.com/Loopring

- zCash-隐私货币网络: https://github.com/zcash/zcash

- zkSync- zkRollup layer2: https://github.com/matter-labs/zksync

- Aztec-layer2隐私网络: https://github.com/AztecProtocol



### dapp

- Dark Forest: zk游戏
  - 合约：https://github.com/darkforest-eth/eth
  - 电路：https://github.com/darkforest-eth/circuits

- zkPoD: 数据交易协议：https://github.com/sec-bit/zkPoD-node
- 

## zk-SNARK组件开发库

**zk-SNARK不同语言实现**

- C++：https://github.com/scipr-lab/libsnark
- Go: https://github.com/ConsenSys/gnark
- native Web Assembly: https://github.com/iden3/wasmsnark
- JavaScript: https://github.com/iden3/snarkjs
- Rust: https://github.com/arkworks-rs/snark

**toolbox**

zkSNARKS on ethereum的工具集：https://github.com/Zokrates/ZoKrates

**电路相关**

- libsnark（C++)

- bellman：构造zk_SNARK电路: https://github.com/zkcrypto/bellman/
- 构造circuit的java library: https://github.com/akosba/jsnark
- 使用Ocaml写R1CS SNARKs（后端使用libsnark）: https://github.com/o1-labs/snarky
- zkSNARK电路集合：https://github.com/HarryR/ethsnarks
- Circom in Rust(电路编译器): https://github.com/iden3/circom/
- ZoKrates: https://github.com/Zokrates/ZoKrates
- Zkinterface(前端兼容多种电路框架): https://github.com/QED-it/zkinterface



**crypto primitives**

- 域/椭圆曲线/多项式运算: https://github.com/arkworks-rs/algebra

- 有限域：https://github.com/zkcrypto/ff

椭圆曲线：

- Jubjub elliptic curve group: https://github.com/zkcrypto/jubjub
-  BLS12-381 pairing-friendly elliptic curve: https://github.com/zkcrypto/bls12_381



**分支算法实现**

bulletproof: https://github.com/dalek-cryptography/bulletproofs

Groth16: https://github.com/zkcrypto/groth16



## 教程

- 基于artwork的snark的教程：In this tutorial, we will construct a SNARK-based rollup for a simple payments systemhttps://github.com/arkworks-rs/r1cs-tutorial/
- 基于libsnark的教程，覆盖创建zk-SNARK电路、产生proof以及验证proof：https://github.com/christianlundkvist/libsnark-tutorial

- 基于SNARK的随机数（使用zkrates）:https://zokrates.github.io/examples/rng_tutorial.html
- bellman demo circuit: https://github.com/ebfull/bellman-demo
- 基于[ethsnarks](https://github.com/HarryR/ethsnarks)搭建的混币和匿名转账dapp: https://github.com/HarryR/ethsnarks-miximus
- ZoKrates -> BulletProofs (基于zkInterface的demo): https://qed-it.github.io/zkinterface-wasm-demo/

- zk技术和应用集合：https://github.com/matter-labs/awesome-zero-knowledge-proofs#snarks
