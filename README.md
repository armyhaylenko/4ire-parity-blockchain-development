# The Great Substrate Course

## The Agenda

### Welcome to the course!

Today marks the day we start learning Substrate and revising Rust. Our Rust revision will be rather long because we want to make sure everyone gets a firm grasp of the required concepts.
For some, it will not be a revision. Instead, you will have to learn Rust from scratch. In two weeks. In three days. So prepare yourself for the ultimate glory! You'll have fun, hehe.

### This is going to be hard

This course will not be easy. Be ready for some good commitment, as Substrate itself is hard and sometimes mundane (high build times). Nevertheless, we will try to make it as interesting as possible!
The estimated commitment for this course is 5hrs a week. This includes 2 hours for the two meetings a week (1 hour for a meeting) and 3 hours for the home tasks.

### This will not be graded

Although this course is very serious in making someone understand Substrate, it is not a certification, nor have I the right to certify people. The assignments will not be graded, and I recommend everyone find a pair and do peer reviews of the home tasks. I encourage discussing implementation details, general approach to the home tasks, and code details.

Since this course is not graded, you don't get to profit from cheating. As opposed to what they say at the universities (you're only harming yourself by cheating), this is the case here. So, you can cheat, of course, I don't care, but I guarantee you'll instantly lose motivation in this course.

### What will be covered

In this course, a couple of important things will be covered. This includes:

* Revision of Rust concepts, which are critical to understanding Substrate:
  * Rust's syntax
  * Ownership & Borrowing
  * Generics + Traits
  * Smart Pointers
  * Rust's memory model
  * Macros
* General blockchain development concepts:
  * Blocks
  * Crypto
  * PKI
  * Fees
  * Consensus algorithms
  * Intro to Smart Contracts
* Ethereum (revision):
  * General architecture
  * Smart contract execution platform architecture
  * Gas model
  * Use cases
* Substrate development key concepts:
  * FRAME
  * Runtime
  * Storage
  * Client libraries
  * Integration
* High-level substrate concepts:
  * Paraobjects
  * Accounts
  * PKI
  * Randomness
  * NPOS
  * Crypto
* Substrate-based smart contracts.

But not limited to.

## The motivation

Why did we choose Substrate in the first place?
Substrate is a great and very versatile blockchain development framework. I enjoy working with it, and this was one of the main motivations for teaching it :P
The motivation to learn it are:
1. High market demand
2. Reflection of all common blockchain development principles in one place (meaning endless space to practice those principles)
3. Despite a steep learning curve, unmatched ease of practical (as in business) use
4. Modernity and increasing adoption

Just take a look at [teams who build in Substrate](https://substrate.io/ecosystem/projects/)!

## Things you will acquire after the successful completion

### The course is hard not just to be hard. It is meant to be rewarding.

After completing the course successfully, you will learn a set of cutting-edge technologies (Substrate, Polkadot, ink!, Rust), one super important skill (blockchain development), one beautiful programming language (Rust), and a wider outlook on the current state of tech, Web3 understanding and most definitely a job among the most interesting Web3 companies around the world.


Next up: Parity company pitch, 4ire company pitch.

## Approximate learning plan

We plan this course to last 5 weeks.

So, the plan approximately goes like this:

### Week 1

* Introduction <-- you're here
* Rust revision (basics)

Materials: [The Book](https://doc.rust-lang.org/nightly/book/title-page.html), [Parity](https://www.parity.io/), [4ire](https://4irelabs.com/), 
**Homework**: Complete chapter 1-10 of The Rust Programming Language


#### Lecture: Meeting Rust

Alright! We're here. Today marks the day we start learning Rust & blockchain development. This course is very oriented toward self-education. Each week, we will have 2 meetings: a lecture and a practice. Moreover, you will get one homework for the week. I don't like grades, so there will be no grading process. All that you do you do for yourself. Everyone here knows what programming is & I advise you to write the best code you can.

So, let's dive right into it:

* [Rust homepage](https://www.rust-lang.org/)

![Rust's advantages](https://i.imgur.com/UPjNxlj.png)

* [Rust wiki page](https://uk.wikipedia.org/wiki/Rust_(%D0%BC%D0%BE%D0%B2%D0%B0_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F))

![Rust wiki page description](https://i.imgur.com/C8sxRdj.png)


* [Rust vs C++](https://codilime.com/blog/rust-vs-cpp-the-main-differences-between-these-popular-programming-languages/)

![](https://i.imgur.com/HBt9lRu.png)


* [Steve Donovan's Rust intro](https://stevedonovan.github.io/rust-gentle-intro/1-basics.html)

![Hello, World!](https://i.imgur.com/3zs8SUa.png)

![Compile error](https://i.imgur.com/rPikb1e.png)

![Variable](https://i.imgur.com/X4bPPu8.png)

![For-loop](https://i.imgur.com/mgm8liM.png)

![Nearly everything is an expression](https://i.imgur.com/LYGcTND.png)

![Immutability](https://i.imgur.com/h7DG2uH.png)


![Functions](https://i.imgur.com/SOfcaZt.png)

![How returns work](https://i.imgur.com/mztyaUg.png)

![Immutable references](https://i.imgur.com/1XFMX8u.png)

![Mutable references](https://i.imgur.com/aKJRDfw.png)

![Arrays](https://i.imgur.com/sd1BRRb.png)

More on arrays: [here](https://stevedonovan.github.io/rust-gentle-intro/1-basics.html#arrays-and-slices)

* [The Book](https://doc.rust-lang.org/nightly/book/title-page.html)

![Ownership intro](https://i.imgur.com/WfnuNjK.png)

![Ownership rules](https://i.imgur.com/eFx2tv4.png)

![Stack-allocated move semantics](https://i.imgur.com/mKf4G73.png)

![Heap-allocated move semantics](https://i.imgur.com/ZuBYpRT.png)


So, as you can see, Rust is a general-purpose programming language, just like a multitude of other languages. At the next meeting, we are going to practice Rust with Rustlings - a fun & interactive way to learn Rust by correcting the code (just like RubyKoans).


#### Practice: Rustlings

Hey everyone! So today is our first practice. During practices, we will mostly look at the code & practical aspects of things we learn during the lectures. I hope to see participation from you, but if not, I will continue with the answer.
Today we are going to take a look at Rustlings. This is an interactive Rust learning app, which I have personally used and attribute a lot of credit to my Rust knowledge to it. We'll work on the problems in Rustlings 
https://github.com/rust-lang/rustlings

![](https://i.imgur.com/pqVvaBu.png)

**What should we add here to make the code compile?**

![](https://i.imgur.com/gRa3r5M.png)

Let's check the formatting [information](https://doc.rust-lang.org/rust-by-example/hello/print.html).



### Week 2

* Rust revision (advanced)
* Blockchain development
* Ethereum

Materials: [The Book](https://doc.rust-lang.org/nightly/book/title-page.html), [What is bitcoin](https://academy.binance.com/uk/articles/what-is-bitcoin), [What is Web3](https://ethereum.org/en/web3/), [Hyperledger Fabric](https://www.hyperledger.org/use/fabric)

**Homework**: Create a simple CLI signer for **ed25519** signatures. Possible libraries: `clap`, `ed25519`, `log`


#### Lecture: Advanced Rust

Alright, since we need to move at a mad pace to complete the course, we'll try & cover everything we need in two lectures this week. The first lecture would be about higher-level Rust, while the second would be about blockchain development. We need to understand high-level Rust to be able to reflect blockchain concepts. 

The high-level Rust we are going to talk about today is traits & generic mostly. Traits are the behavior inheritance mechanism in Rust. They are similar to interfaces in other languages (but not quite).

* [Traits](https://doc.rust-lang.org/book/ch10-02-traits.html)

![](https://i.imgur.com/WiEOTID.png)

Traits are collections of some data-agnostic behavior. That's the bottom line.

We can define a trait the following way:
![](https://i.imgur.com/1PJH0am.png)

Let's look at how to implement a trait for a type:
![](https://i.imgur.com/Bc8aIHF.png)

As we can see, we don't use the `content` field of `NewsArticle`. We don't need the contents in the summary.

Now, can the traits have a default implementation? Turns out they can! That is unlike in many other languages.
![](https://i.imgur.com/59gEMiK.png)

Here, we don't use `self` as we cannot know, which fields the implementer has.

Though, we can control that in a way - let's take a look in the advanced traits section.


* [Advanced Traits](https://doc.rust-lang.org/book/ch19-03-advanced-traits.html#fully-qualified-syntax-for-disambiguation-calling-methods-with-the-same-name)


Types in Rust might implement a lot of traits. It is not uncommon for some traits to have methods with equal names. Moreover, if a type has a method, say, `foo`, it's possible to implement a multitude of traits with the method `foo` on this type.

"When calling methods with the same name, you’ll need to tell Rust which one you want to use. Consider the code in Listing 19-16 where we’ve defined two traits, `Pilot` and `Wizard`, that both have a method called `fly`. We then implement both traits on a type `Human` that already has a method named `fly` implemented on it. Each `fly` method does something different." (https://doc.rust-lang.org/book/ch19-03-advanced-traits.html)
![](https://i.imgur.com/tCE8THI.png)

So, how do we differentiate between those different methods? How do we call them?

Question: What will this code do?
![](https://i.imgur.com/NkYj1kZ.png)

Below we show how to call the methods of different traits on some value.
![](https://i.imgur.com/SK98p4J.png)

![](https://i.imgur.com/xy2zsQS.png)


"However, associated functions that are not methods don’t have a self parameter. When there are multiple types or traits that define non-method functions with the same function name, Rust doesn't always know which type you mean unless you use fully qualified syntax. For example, the `Animal` trait in Listing 19-19 has the associated non-method function `baby_name`, and the `Animal` trait is implemented for the struct `Dog`. There’s also an associated non-method function `baby_name` defined on `Dog` directly." (https://doc.rust-lang.org/book/ch19-03-advanced-traits.html)
![](https://i.imgur.com/bR1PKEH.png)

![](https://i.imgur.com/7QwC0tk.png)

Generally, to disambiguate the type, we need to use the following syntax:
`<Type as Trait>::method(args)`

Here's an example that refers to our Animal hierarchy:
![](https://i.imgur.com/OYou02A.png)
This is heavily used in Substrate, as we will see later.


There's also one more thing we need to know: supertraits and trait bounds.
Let's look at another example from the Book.
![](https://i.imgur.com/FPMfaZX.png)

![](https://i.imgur.com/5dcAqGt.png)

![](https://i.imgur.com/D2DYTN1.png)
![](https://i.imgur.com/6NCqNKf.png)

Let's take a look at the complete, working example.

![](https://i.imgur.com/A7YBBLG.png)



Now, as we got traits fully out of the way, let's dive into macros. It might seem intimidating at the first glance, but I promise they'll make sense in the end!

* [Macros](https://doc.rust-lang.org/book/ch19-06-macros.html)

So, in short, macros are a compile-time code generation tool. They are very different from the macros we are used to in C and C++: these macros are hygienic. You can read more about macro hygiene [here](https://en.wikipedia.org/wiki/Hygienic_macro).

![](https://i.imgur.com/4tsLtZV.png)
![](https://i.imgur.com/1WLgf8I.png)

This example shows us the `vec!` macro. We can use `vec` to conveniently create vectors with some elements (like with an initializer in cpp):

```rust=
fn main() {
    let my_vec = vec![1, 2, 3, 4, 5];
    my_vec.into_iter().for_each(|item| println!("{item}"))
    // this is a new syntax for printing captured vars,
    // btw
}
```

So, in the macro definition, we can see some weird syntax with dollar signs, types, stars, etc.
In our scope, we will not look into how macros work, but in general, those are syntactic constructs that define some calling syntax and output some code on invocation (during compilation).

So in our case, the `vec!` invocation will turn into this:

```rust=
fn main() {
    let my_vec = {
        let mut temp_vec = Vec::new();
        temp_vec.push(1);
        temp_vec.push(2);
        temp_vec.push(3);
        temp_vec.push(4);
        temp_vec.push(5);
        temp_vec
    };
    my_vec.into_iter().for_each(|item| println!("{item}"))
}
```

Another type of macros is procedural macros. They look like this:
`#[some_attribute]`.

We won't look much into them, only how to use them. The general difference between procedural & declarative macros is that procedural macros are full-blown programs running in the compiler, while declarative macros are kinda like functions for code generation. Procedural macros operate on `TokenStream`s, while their declarative counterparts operate on concrete language constructs: expressions, literals, types, visibility items, and other stuff.


Today we've taken a look at the most important features of advanced Rust used in Substrate. That's on top of *all* of the basic features, of course.
This is the end of our Rust study/revision. Next, we will have some theoretical stuff to work through, but then we'll get to writing Substrate. This will be one big practice for Rust, as well as blockchain development concepts we'll learn about next.


#### Lecture 2

Hello again, everyone! Today is the second lecture of our week. In this lecture, we'll be talking about blockchains in general. We'll work using a [blockchain learning path](https://github.com/protofire/blockchain-learning-path) kindly provided by Kyrylo Gorokhovskyy to me. We'll cover the basics as much as possible.

So, let's start with simple things: primitives of blockchain technology.

![](https://i.imgur.com/84WMJvG.png)
![](https://i.imgur.com/gVQR9Qh.png)

After we got the crypto intricacies out of the way, let's check how bitcoin works. This will take some time.


After covering the most basic stuff (hashes, digital signatures, cryptography, PKI, and so on), we will move on to covering [bitcoin](https://academy.binance.com/uk/articles/what-is-bitcoin). Bitcoin is the first cryptocurrency, but it is advanced. It is worth understanding how it works.

[This](https://www.researchgate.net/publication/349787845_Blockchain_in_Cyberdefence_A_Technology_Review_from_a_Swiss_Perspective/figures?lo=1) is the anatomy of the node:
![](https://i.imgur.com/yKp1GTe.png)

After getting an understanding of how Bitcoin works, let's take a look at its consensus algorithm: [Proof of Work](https://academy.binance.com/uk/articles/proof-of-work-explained).
One great [video](https://www.youtube.com/watch?v=bBC-nXj3Ng4) on how bitcoin works.



### Week 3

**Homework**: go through all of the materials, and finish the Ethereum article.

#### Lecture: Ethereum, smart contracts

Understanding the first advanced smart contract platform, Ethereum, is essential to understanding the whole blockchain development fuss. Ethereum was the first blockchain to show that one can write decentralized programs, which would be verified by all network participants.

You might ask, why they are called contracts.
Well, to be fair, I don't know. But I'm pretty sure it was some gimmick to attract business people to adopt Ethereum. Anyways.

Today we'll spend most of the lecture revising how Ethereum works, so prepare yourself for a pretty big journey [here](https://preethikasireddy.medium.com/how-does-ethereum-work-anyway-22d1df506369).

Let's look at the blockchain definition from the article:
![](https://i.imgur.com/th1q6KC.png)

A more detailed explanation of Ethereum's paradigm:
![](https://i.imgur.com/isOfoJu.png)


![](https://i.imgur.com/rPnYY5T.png)

Here we can see a diagram of how the state progresses within the blockchain.
The possible state changes between some block `N` and block `N+1` can be described by a `state transition function`. The state transition function is the whole collection of things that can change the chain state - smart contract calls, logs, balance transfers, paying fees, etc.
In other words, we can define everything that happens on a blockchain by its `state transition function`. This is a common thing for all blockchains that contain any logic - even bitcoin. Bitcoin script executions, UTXO assignment - those are the parts of the state transition function of bitcoin.
This is an important term to remember, as Substrate has its state transition function, too. In Substrate, the state transition function is fully customizable and is named `runtime`.

![](https://i.imgur.com/8lR8dmT.png)

This diagram shows us the results of the process of block production. When we produce blocks, we might naturally get forks, because different validator nodes might be on different blocks when producing the next block. To choose the correct block, we need some mechanism. This mechanism is different from blockchain to blockchain, but since we're talking about Ethereum now, let's look at GHOST.
![](https://i.imgur.com/exzf8om.png)

We deem the blocks which base on the longest finalized chain as correct.
Polkadot has something similar:
![](https://i.imgur.com/Cav6EUF.png)

We're not going to get much deeper than that. This understanding of finality should be enough.

Now, let's look at the account model of Ethereum:
![](https://i.imgur.com/ZsdSiKh.png)

Below we can see a diagram of how transactions are initiated on Ethereum:
![](https://i.imgur.com/AnfeWDL.png)

Now, let's take a look at another important, defining thing in Ethereum & account-based blockchains as a whole. The state of the blockchain is described by the ledger (connected blocks), but we also have the state, *which is attached to each account*. This state contains the transactions initiated by this account, the balances, etc. For contracts, this state also contains the code hash of the contract.

The state is described using Merkle Patricia trees, analogously called *tries*. ![](https://miro.medium.com/max/1400/1*5xWwPX2R8d37MeWSFOJPnA.png)

Let's take a deeper look into the article and talk about **gas** and **smart contracts**.



If we still have time after taking on this beast of an article, well, we can have some QnA time to discuss everything covered before.


#### Lecture: Substrate

Hello again, everyone! Today is the day we finally start learning Substrate. We've covered a lot in the previous two weeks, so let's use our knowledge in our main learning subject - Substrate.

Substrate is a framework that allows us to build efficient, future-proof, and modular blockchains with a LOT of features provided out of the box.

Let's take a look at the general architecture of Substrate. What provides the flexibility of Substrate? The answer is FRAME. This architectural part is responsible for modularizing functionality, allowing for hot swaps & runtime code upgrades.

* [General node architecture](https://docs.substrate.io/v3/getting-started/architecture/)

![Substrate node architecture](https://d33wubrfki0l68.cloudfront.net/5c60d8b81eb636cec461b68c6017c7e26475d869/325c0/static/262e7fe9f1f7d3db5dd8cee450d77c86/eff3b/substrate-arch.png)
This is the architecture of a substrate client (read *substrate node*). As we can see, it has several things in it:
1) P2P Networking module
2) RPC module
3) Storage with the WASM runtime in it
4) Consensus module
5) Telemetry module
6) Native runtime

Let's quickly take a look one by one:

- The P2P networking module is responsible for transaction propagation. When a node receives a transaction via an RPC call, the node must propagate this transaction to the peers so that the whole network executes it.
- RPC is responsible for receiving the transaction calls & hosting different host function endpoints (as in chain-specific functions).
- Consensus is the module that is responsible for, you guessed it, consensus. The consensus is pluggable, meaning we can choose different consensus algorithms for different chains.
- Telemetry is just some endpoints that transmit node metrics.
- Native runtime is everything available for use in and outside of the WASM runtime: same and more functions, same and more modules. The native runtime was created to overcome the slowness of the WASM runtime, but it cannot provide guarantees of equal execution of STF between different nodes. Simply, if you're gonna expect equal computation results of equal calls on different nodes, you might not get them.



* [Runtime architecture](https://docs.substrate.io/v3/concepts/runtime/)


"`The runtime of a blockchain is the business logic that defines its behavior. In Substrate-based chains, the runtime is referred to as the "state transition function"; it is where Substrate developers define the storage items that are used to represent the blockchain's state as well as the functions that allow blockchain users to make changes to this state.`" (https://docs.substrate.io/v3/concepts/runtime/)
![](https://docs.substrate.io/static/165c3188f678dcd2cbd3999cbab04b7c/ea64c/substrate-runtime-client.png)

As we can see, everything that makes a chain special in terms of its application logic is compiled to WASM and stored in the storage. Everything else is either part of each node (tx pool, finality, storage, block production, RPC, p2p server, native runtime).


* [FRAME](https://docs.substrate.io/v3/runtime/frame/)

FRAME is an architectural approach to building a substrate node, which makes the chain flexible and easily upgradeable.
FRAME stands for the *Framework for Runtime Aggregation of Modularized Entities*. That's a mouthful.
![](https://docs.substrate.io/static/3499b4465d746bd0dcb22e34779d5546/97a96/frame-arch.png)
Looking at this diagram, we see the following:
- Runtime. Runtime is composed of default/custom FRAME *pallets*, execution module, support library, and the system module.
- The Executive is responsible for executing the transactions within a block, progressing block state, and other core block-related things.
- Runtime modules fill our runtime with logic - we can add the Balances pallet to track the balances of an account, the Transaction Payment pallet to enable the payments for the transaction execution, the Timestamp pallet to insert block timestamps, and much more.
- The System module is mainly responsible for managing how our runtime is constructed, managing transaction origins, etc.
- The Support Library is just a collection of useful *traits*, *macros* and other stuff related to our blockchain.

Out of all those things, the `Runtime Modules` we choose to make our runtime special.


Now, let's talk about the transactions, cause what is a blockchain without transactions?!

* [Extrinsics](https://docs.substrate.io/v3/concepts/extrinsics/)

Let's take a look at the definition of an *extrinsic*:

`An extrinsic is a piece of information that comes from outside the chain and is included in a block. Extrinsics fall into three categories: inherents, signed transactions, and unsigned transactions.`

So, how is it different from `transactions`?
Answer:
`A block in Substrate is composed of a header and an array of extrinsics. The header contains a
block height, parent hash, extrinsics root, state root, and digest.`

Extrinsics are very similar to transactions. The difference is rather in the etymology of the word itself - *transactions* are thought of as something that has a monetary value (or execute some logic in the case of blockchains), while *extrinsics* are more generally pieces of external information.

Frankly, we, Substrate devs, use *transactions* and *extrinsic* interchangeably.

Let's talk about signed and unsigned transactions.
The difference is mostly inferred from the name. Signed transactions are signed by network participants (as in people), while unsinged txs are not signed by anyone. This means we have to define custom validation logic for those transactions.
Signed transactions are like Ethereum transactions, while unsigned transactions can be thought of more like system-related transactions. One must use it with care because since no one signs those txs, no one pays the fee.

* [Weights](https://docs.substrate.io/v3/concepts/weight/)

When we use our blockchain, the gas is used to provide to miners for the following:
![](https://i.imgur.com/J2mrKeV.png)

Substrate does not use the concept of **gas**, as it doesn't have predefined opcodes like the smart contracts in Ethereum. Instead, we pay based on the length of our tx, state changes & **the time consumed for the computation**. You might say that on each node the execution times might be different, and you would be right. That's why Substrate standardizes hardware, based on which the weights are estimated.

![](https://i.imgur.com/bNJm9s1.png)


![](https://i.imgur.com/x1YJt4V.png)

```
inclusion_fee = base_fee + length_fee + [targeted_fee_adjustment * weight_fee];
final_fee = inclusion_fee + tip;
```

Materials: [Substrate docs](https://substrate.io/), [Polkadot wiki](https://wiki.polkadot.network/docs/getting-started)


### Week 4

**Homework**: Create a faucet that mints tokens to the requestor every, say, 16 blocks, meaning the requestor cannot get tokens if 16 blocks had not passed since the last mint. Also, since this transaction is lightweight and cannot be repeated more than 1 time in 16 blocks, **disable** transaction fees for that. The transaction must be signed.
You can do the minting using the `Currency` trait and setting it to `pallet_balances`'s implementation (Balances in `runtime/lib.rs`). Use `issue` and `resolve_into_existing` methods. The implementation is totally up to you (minting right away, approving mints by superuser/governance - how far you want to go).
More on that: [tight pallet coupling](https://docs.substrate.io/how-to-guides/v3/pallet-design/tight-coupling/), [Currency trait](https://docs.substrate.io/rustdocs/latest/frame_support/traits/tokens/currency/trait.Currency.html).

#### Practice: Substrate FRAME

Alright, so here comes our practice. During the previous lecture, we discussed how Substrate generally works, while also checking out Extrinsics & Weights. That's the most important info we should know to get right into Substrate development.

During this practice, we will complete [this](https://docs.substrate.io/tutorials/v3/create-your-first-substrate-chain/) tutorial.

Let's dive right into this.
Before we start with the code, I'd like to go over some theoretical aspects of a blockchain node, which are provided in the tutorial.
![](https://i.imgur.com/ni25pLi.png)

So, as we have seen before, a blockchain node consists of a couple of things.
The **storage** is responsible for storing all of the accounts / UTXO data, the code to run, blockchain metadata & so on. Some nodes have a more extensive storage use (like Substrate, which uses storage for all of the STF code), and some have a less extensive storage use (like Bitcoin).
The **P2P** networking is an essential part of a blockchain node, since it is responsible for propagating the transactions among the node's peers, and receiving such [**gossip**](https://academy.binance.com/en/glossary/gossip-protocol).
The **consensus** says everything for itself.
These **data handling capabilities** imply having some RPC/REST set up to receive the transactions, which are ultimately this **extrinsic information**.
A **runtime** is that thing we talked about in the last lecture.

Now, let's go to the page of this tutorial & complete it.


(If we have time, we might take on [Nicks pallet tutorial](https://docs.substrate.io/tutorials/v3/add-a-pallet/)).


#### Practice: runtime upgrades & governance

Hey! Getting familiar with Substrate already? Well, this week you'll become even **more** familiar with it.
Today we are talking about more core features of Substrate that make it a great framework. And the first one I'd like to talk about is **forkless runtime upgrades**. This is a technique to update the `runtime` (remember, the state transition function) without actually redeploying the nodes.
This is possible thanks to a WASM runtime. Since the code is just some bytes stored within the node's storage under some key, we can easily update it, just like we update values in a database.
Of course, not all network participants can arbitrarily update the code for all nodes. This requires some higher privileges. While it is possible to do using `pallet-sudo`, having one privileged user within a decentralized network isn't typically a best practice. Instead, production chains (Polkadot, Kusama, Moonbeam, Acala, etc.) use various governance mechanisms to vote for an upgrade and update the code collectively. In this way, this DAO-based approach pretty much reflects modern governmental systems, with elections, voting, etc.

So, without further ado, let's get to it!

[**Forkless Upgrade tutorial**](https://docs.substrate.io/tutorials/get-started/forkless-upgrade/)

To summarize, we checked out the Scheduler pallet & how to do forkless runtime upgrades.

Now, to do proper upgrades, we'll have to use some decentralized approach for deciding on the feasibility, security, and importance of an upgrade. [`pallet-collective`](https://github.com/paritytech/substrate/tree/master/frame/collective) will help us with that.
To wrap things up, I'd like to check out the governance, presented on Polkadot & implemented using Substrate. [here](https://wiki.polkadot.network/docs/learn-governance).



### Week 5


#### Lecture - ink! and smart contracts
Hello everyone! Today is the beginning of week 4 of our course. Today's topic is **`ink! and smart contracts`**.

ink! and smart contracts in Substrate are **not** the most popular thing in the ecosystem. Although it's rigorously discussed within the community, no parachain (as of May 2022) supports WASM-based smart contracts in production (as in Polkadot, Kusama, etc.).

Then why would we take a look at it?! Well, ultimately, it's because we become better programmers when we learn from different languages, frameworks, etc. Moreover, we start to better understand the intrinsics of a system. In our case, we might compare Solidity/Near SDK/Solana Programs/etc to ink!, see commonalities and differences.

Let's dive right into it.
ink! is an `eDSL` for `pallet-contracts`-based smart contracts. ink! is compiled to WASM.
So, in other words, ink! is a language in which we write smart contracts (mind you, ink! is also valid Rust), then it compiles to WASM, then this WASM code gets executed in `pallet-contracts`. `pallet-contracts` is a stack-based virtual machine that supports WASM evaluation, memory, etc.
As opposed to Solidity, ink! is not compiled to bytecode, which means it does not have its set of opcodes to operate with. Consequently, the concept of "gas" is very different in `pallet-contracts` rather than `EVM`.

With this general info, we might proceed & take a look at the practical part [**here**](https://docs.substrate.io/tutorials/smart-contracts/first-smart-contract/)!

Materials: [ink! docs](https://paritytech.github.io/ink-docs/), [Openbrush](https://openbrush.io/), [ink! tutorial](https://docs.substrate.io/tutorials/smart-contracts/first-smart-contract/)

**Homework**: Create a mintable-burnable PSP22 token using Openbrush (no UI integration needed).

#### QnA - Integrating a real-world application with blockchain & QnA with Gautam Dhameja

Materials: [How to integrate a blockchain with a business](https://medium.com/swlh/blockchain-integration-a-step-by-step-guide-7371f49c72e1)

So, this will be the last meeting in this course. We already covered a lot, had massive amounts of practical tasks, and learned a bit about the usage of Substrate.
Today I'd like to invite Gautam Dhameja, Director of Solution Delivery @ Parity Technologies.

So, what I'd like to go through:
* **Parachains, parathreads, relay chains - how to go from a Substrate chain running locally to the one real people are using**

So, the stuff related to [architecture](https://wiki.polkadot.network/docs/learn-architecture):
- [Parachains](https://wiki.polkadot.network/docs/learn-parachains)
- [Parathreads](https://wiki.polkadot.network/docs/learn-parathreads)



* **What is the benefit of using Polkadot, as opposed to say Ethereumv2**

- [The difference between Eth2.0 & Polkadot](https://wiki.polkadot.network/docs/learn-comparisons-ethereum-2)
* **Smart contracts vs custom blockchain**

- [The difference between building a solution in ink!/EVM vs building a parachain](https://wiki.polkadot.network/docs/build-smart-contracts#difference-between-developing-a-smart-contract-and-a-parachain)
* **How to build a business model around a Substrate-based blockchain**


# Our logical conclusion

This course has come to an end. We've covered a lot. I am sure that those who attended every meeting have learned something new, something that widens the outlook for the developer inside.
I will always be happy to see you as builders, somewhere in the Web3 space, or just quietly enjoying Rust, even as a fun activity.

