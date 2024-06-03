RSA
===

RSA (Rivest–Shamir–Adleman) is a fundamental public-key cryptosystem used for secure data transmission. Introduced in 1977 by Ronald Rivest, Adi Shamir, and Leonard Adleman, RSA employs a pair of keys: a public key for encryption and a private key for decryption. The security of RSA relies on the computational difficulty of factoring large composite numbers, specifically the product of two large prime numbers. Key generation involves selecting two large prime numbers, calculating their product, and deriving the public and private keys from these values. This mechanism ensures that data encrypted with a recipient's public key can only be decrypted with their private key, safeguarding the confidentiality of the transmitted information.

Read more from [here](https://web.archive.org/web/20230127011251/http://people.csail.mit.edu/rivest/Rsapaper.pdf)

Task
===

In this task you are given components for constructing the RSA public and private key. We have given you `n`, `e`, and `d` components in [hex encoding](https://en.wikipedia.org/wiki/Hexadecimal). Further you are given a encrypted hex encoded message (`c`) using the **public key** constructed from the above components.

`n=a674f0f2a01fa0a987d0ef355f36cbd7eda5a931d5eca30b18fc237a481fcea435fe514166db877ca1e645204b0e1e2a8e5f7fcf28a98306c70424f0f4025c7d8c6d89063ac7847bf52eb1f2852bdd5cc03c1cbf63875b5062f4d22b290526a5fecfe343d39c3b46626b63e91670802b4d7a066973474a757d3e5957ddc020afddbeef963643b237651f7bd58d9af4ea67da7de5620539fb904c5a0243388498013470de777c8f11924add97fa1fb11b51cab46ea38adf995ad5efd0958a98cbf022dfb0d4b128917e4b513f120629051307b4d9d1014a28c55c93aaff59f47a7c0472a8b7a1ad5dbf07252c4b2602278fe18a77ec8acb8798f9f8b720dafe03`

`e=f3e7af`

`d=19f9641ecc4e21405d238542fc633a35a33f3ddc84dfb8dc000c27bdfbb5128c0ae3b561ca615aabf7223824d6415a8a6285ca781683aa76ab9c8542dc02bc50ce60770246fa565a1975f6ce508d3cfc30b24b7eccc02183c5bf6a9b7900d621cb3e97fe57031574ab9e54b0eb2040415262cb7f354e032c39453ac38c51d9f9d98bccde0b866d5bbb4013b84054d55ecf8677a3af7308898ef03d30c796cb020aab69002ac00e820fd0bdb176c20589eee572f8699c27353dea73f7ea9b6c83a55d05f7eec7bb77244f11895ff0f462893ead61d8e51c55eea2ffc5b522c0b86fcde09c785f418570d071ddd39d8c3c3a05d80ef51a081ed3749180b973f24f`

`c=   `



Use any of your preferred programming language with a suitable crypto library and decrypt the cypher text using the **private key** constructed from given components and ontain the plain text message (`m`) in hex encoding. 

Convert the `m` from hex encoding to [ascii encoding](https://en.wikipedia.org/wiki/ASCII) and obtain the string `s`. Finally, send us the resulting string `s`. 

`m = # you find this out`

`s = # send us this in your email`


You may need to read the [paper](https://web.archive.org/web/20230127011251/http://people.csail.mit.edu/rivest/Rsapaper.pdf) to figure out the correct components to construct the public and private keys. Remember the given components of `n`, `e`, and `d` are **hex encoded**.

> Hint : Resultant string is a string that contains valid words in english language. 


-----
_This task was created by [Archfx](https://github.com/archfx)_
