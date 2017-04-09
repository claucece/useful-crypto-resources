# Useful Crypto-related Resources

### AKE
* [An Efficient Protocol for Authenticated Key Agreement](http://cacr.uwaterloo.ca/techreports/1998/corr98-05.pdf) by Laurie Law, Alfred Menezes, Minghua Qu, Jerry Solinas.
* [Two-party authenticated key exchange protocol using lattice-based cryptography](https://eprint.iacr.org/2016/761.pdf) by Xiaopeng Yang and Wenping Ma

## OTR

### OTRv2

* [Finite-State Security Analysis of OTR Version 2](http://www.jbonneau.com/doc/BM06-OTR_v2_analysis.pdf) by Joseph Bonneau and Andrew Morrison.
* [Protocol](https://otr.cypherpunks.ca/Protocol-2.0.2.txt) by Nikita Borisov and Ian Goldberg.
* [Secure Off-the-Record Messaging](https://www.dmi.unict.it/diraimondo/web/wp-content/uploads/papers/otr.pdf) by Mario Di Raimondo, Rosario Gennaro and Hugo Krawczyk

### Multiparty
* [Multi-party Off-the-Record Messaging](https://www.cypherpunks.ca/~iang/pubs/mpotr.pdf) by Ian Golberg et Al.

## Zero Knowledge Proof
* [Multiple Non-Interactive Zero Knowledge Proofs Based on a Single Random String](https://www.computer.org/csdl/proceedings/focs/1990/2082/00/089549.pdf) by Uriel Feige, Dror Lapidot and Adi Shamir.

## Ciphers

* [So you want to use an alternative cipher…](https://blog.cryptographyengineering.com/2012/10/09/so-you-want-to-use-alternative-cipher/) by Matthew Green.
* [Why switch from AES to a new stream cipher?](https://cr.yp.to/streamciphers/why.html) by Daniel Bernstein.

### Stream cipher

#### Salsa 20
* [Salsa20 security](https://cr.yp.to/snuffle/security.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.

#### XSalsa20
* [Extending the Salsa20 nonce](http://cr.yp.to/snuffle/xsalsa-20081128.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.
* [Implementation](https://github.com/golang/crypto/blob/master/nacl/secretbox/secretbox.go) in NaCl

### Blockcipher

#### In general
* [Evaluation of Some Blockcipher Modes of Operation](http://web.cs.ucdavis.edu/~rogaway/papers/modes.pdf) by Phillip Rogaway.

## Symmetric key algorithm

### DES
* [On the Security of Multiple Encryption](http://cs.jhu.edu/~sdoshi/crypto/papers/p465-merkle.pdf) by Ralph C. Merkle and Martin E. Hellman

## Key Exchange

### Degenerate
* [Degenerate Keys for RSA Encryption](https://pdfs.semanticscholar.org/2a2e/6585b83949cc13e58444f7b4435cf76d2920.pdf) by Seth D. Bergmann.
* [Info](https://books.google.de/books?id=amW5BQAAQBAJ&pg=PA205&lpg=PA205&dq=check+for+degenerate+key+crypto&source=bl&ots=IChUHyW5O8&sig=WC1JF6QumuLoX_k9lnql_5Aee8c&hl=es-419&sa=X&sqi=2&ved=0ahUKEwjQybzEsZDSAhVnwYMKHfjFDHsQ6AEILDAC#v=onepage&q=check%20for%20degenerate%20key%20crypto&f=false)
* [Degenerate Curve Attacks](https://eprint.iacr.org/2015/1233.pdf) by Samuel Neves and Mehdi Tibouchi

### Diffie Hellman
* [New directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) by Diffie and Hellman.
* [Diffie-Hellman key exchange](http://www.math.ucla.edu/~baker/40/handouts/rev_DH/node1.html) by Nikos Drakos
* [Diffie-Hellman Key Agreement Method](https://www.ietf.org/rfc/rfc2631.txt) by E. Rescorla
* [Diffie-Hellman parameters](https://wiki.openssl.org/index.php/Diffie-Hellman_parameters) by OpenSSL
* [Imperfect Forward Secrecy: How Diffie-Hellman Fails in Practice](https://weakdh.org/imperfect-forward-secrecy-ccs15.pdf) by David Adrian et al
* [Diffie-hellman](https://www.cryptopp.com/wiki/Diffie-hellman#Key_Agreement_and_Transport) by Crypto++
* [Public key parameters](http://cacr.uwaterloo.ca/hac/about/chap4.pdf#page=164)
* [A One Round Protocol for Tripartite Diffie–Hellman](https://pdfs.semanticscholar.org/845e/96c20e5a5ff3b03f4caf72c3cb817a7fa542.pdf) by Antoine Joux

#### Validation
* [Additional Diffie-Hellman Tests for the Internet Key Exchange Protocol Version 2](https://tools.ietf.org/html/rfc6989#section-2.1) by Y. Sheffer Porticor, S. Fluhrer

#### Attacks
* [Timing Attacks on Implementations of Diffie-Hellman, RSA, DSS, and Other Systems](https://42xtjqm0qj0382ac91ye9exr-wpengine.netdna-ssl.com/wp-content/uploads/2015/08/TimingAttacks.pdf) by Paul C. Kocher
* [On reusing ephemeral keys in Diffie-Hellman key agreement protocols](http://cacr.uwaterloo.ca/techreports/2008/cacr2008-24.pdf) by Alfred Menezes and Berkant Ustaoglu

### Cramer-Shoup
* [Cramer Shoup Cryto-System Java implementation](https://github.com/omoeller/cramshou) by omoeller (not audited).
* [Cramer Shoup Cryto-System Python implementation](https://github.com/benkreuter/cca2python) by benkreuter.

### Elliptic Curve

#### Theory
* [Elliptic Curves Number Theory and Cryptography](http://people.cs.nctu.edu.tw/~rjchen/ECC2012S/Elliptic%20Curves%20Number%20Theory%20And%20Cryptography%202n.pdf) by Lawrence C. Washington
* [Isogenincs](http://math.mit.edu/classes/18.783/LectureNotes5.pdf) for a MIT class.
* [Compact representation of an elliptic curve point](https://tools.ietf.org/html/draft-jivsov-ecc-compact-05): This document defines a format for efficient storage representation of an elliptic curve point over prime fields, suitable for use with any IETF format or protocol by A. Jivsov
* [Point Generation And Base Point Selection In ECC: An Overview](http://www.ijarcce.com/upload/2014/may/IJARCCE7J%20%20a%20moumita%20Point%20Generation%20And%20Base.pdf) by Moumita Roy1, Nabamita Deb2, Amar Jyoti Kumar.
* [SEC 1: Elliptic Curve Cryptography](http://www.secg.org/sec1-v2.pdf) by Certicom Research.
* [Elliptic Curves for Security](https://www.ietf.org/rfc/rfc7748.txt) by A. Langley and M. Hamburg. This memo specifies two elliptic curves over prime fields that offer a high level of practical security in cryptographic applications, including Transport Layer Security (TLS).  These curves are intended to operate at the ~128-bit and ~224-bit security level, respectively, and are generated deterministically based on a list of required properties.
* [ECC2015-Notes](https://github.com/FredericJacobs/ECC2015-Notes) by Frederic Jacobs
* [Graphs](https://cryptojedi.org/misc/pstricks.shtml)
* [How to design an elliptic-curve signature system](https://blog.cr.yp.to/20140323-ecdsa.html) by blog.cr.yp.to
* [Generating Elliptic Curves of Prime Order](http://people.oregonstate.edu/~schmidtt/ourPapers/SavasKoc/ches01curve.pdf) by Erkay Sava, Thomas A. Schmidt, and Cetin K. Koc
* [Extended coordinates with a=-1 for twisted Edwards curves](http://www.hyperelliptic.org/EFD/g1p/auto-twisted-extended-1.html)
* [Elliptic Curves Suitable for Cryptosystems](https://grampus.jaist.ac.jp/miyaji-lab/member/PaperPS/SCIS93-10B.pdf) by Atsuko Miyaji
* [Elliptic curves](http://library.msri.org/books/Book44/files/07poonen.pdf) by Bjorn Poonen
* [Rigid Parameter Generation for Elliptic Curve Cryptography](https://tools.ietf.org/html/draft-black-rpgecc-01#page-6) by B. Black
* [Tutorial](https://www.youtube.com/watch?v=w2V2dyL1LO8) by Tanja Lange
* [ECC hacks](https://www.youtube.com/watch?v=vEt-D8xZmgE) by Tanja Lange
* [Curves Formulas](http://www.hyperelliptic.org/EFD/) by Tanja Lange
* [512-bit twisted Edwards curve and curve generation methods in Russian standardization](https://www.ietf.org/mail-archive/web/cfrg/current/msg05975.html) by Stanislav V. Smyshlyaev
* Programming: [Sage: Elliptic curves over a general field](http://doc.sagemath.org/html/en/reference/curves/sage/schemes/elliptic_curves/ell_field.html)
* [Weierstrass coefficients of the canonical lifting](https://www.math.utk.edu/~finotti/papers/wcoef.pdf) by Luis R. A. Finotti
* [Weierstrass equation or model](http://www.lmfdb.org/knowledge/show/ec.weierstrass_coeffs)
* [Elliptic Curves, Lattices, and the Upper Half-Plane](https://www.hdevalence.ca/blog/2012-10-31-elliptic-curves-lattices-and-the-upper-half-plane)
* [Elliptic Curve Cryptography: a gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/) by Andrea Corbellini
* [Curves with a Twist](https://ripple.com/dev-blog/curves-with-a-twist/)
* [Elliptic vs Hyperelliptic](https://www.yumpu.com/en/document/view/51546701/tanja-lange) by Tanja Lange
* [Sign Change Fault Attacks On Elliptic Curve Cryptosystems](https://eprint.iacr.org/2004/227.pdf) by Johannes Blömer, Martin Otto and Jean-Pierre Seifert
* [An exploration of affine group laws for elliptic curves](https://www.degruyter.com/view/j/jmc.2011.5.issue-1/jmc.2011.005/jmc.2011.005.xml) by Huseyin Hisil, Kenneth Koon-Ho Wong, Gary Carter and Ed Dawson

#### Twist
* [Twist Insecurity](http://eprint.iacr.org/2015/577.pdf) by Manfred Lochter and Andreas Wiemers

#### Jacobic
* [The Jacobi Model of an Elliptic Curve and Side-Channel Analysis](https://eprint.iacr.org/2002/125.pdf) by Olivier Billet and Marc Joye

#### In general
* [Elliptic Curves for Security draft-irtf-cfrg-curves-02](https://tools.ietf.org/html/draft-irtf-cfrg-curves-02#section-6.2): an algorithm for deterministically generating parameters for elliptic curves over prime fields by A. Langley.
* [Elliptic Curves for Security](https://tools.ietf.org/html/rfc7748) by A. Langley and M. Hamburg.
* [A brief discussion on selecting new elliptic curves](http://csrc.nist.gov/groups/ST/ecc-workshop-2015/papers/session4-costello-craig.pdf) by Craig Costello, Patrick Longa, and Michael Naehrig
* [Curve41417: Karatsuba revisited](http://eprint.iacr.org/2014/526.pdf) by Daniel J. Bernstein, Chitchanok Chuengsatiansup, and Tanja Lange
* [Cryptography in NaCl](https://cr.yp.to/highspeed/naclcrypto-20090310.pdf) by Daniel J. Bernstein. Pretty interesnting for sage.
* [Subtraction](http://crypto.stackexchange.com/questions/11316/subtracting-a-point-in-elliptic-curve-cryptography)
* [Elliptic curve point multiplication](https://en.wikipedia.org/wiki/Elliptic_curve_point_multiplication) in Wikipedia.
* [Explicit Addition Formulae](https://crypto.stanford.edu/pbc/notes/elliptic/explicit.html)
* [Elliptic curve point multiplication](https://en.wikipedia.org/wiki/Elliptic_curve_point_multiplication#Point_multiplication)

#### Conversions
* [Fault Attacks on Projective-to-Affine Coordinates Conversion](https://cosade.telecom-paristech.fr/cosade13/presentations/session2_b.pdf) by Diana Maimut, C´edric Murdica, David Naccache and  Mehdi Tibouchi. Presentation
* [Fault Attacks on Projective-to-Affine Coordinates Conversion](https://books.google.com.ec/books?id=c_y5BQAAQBAJ&pg=PA46&lpg=PA46&dq=toaffine+ecc&source=bl&ots=twi-3g-Ea7&sig=UWNbVQLkW-DSKAk0E2Bw-bG5I4s&hl=en&sa=X&ved=0ahUKEwjajLqVh6LSAhUp04MKHVWZDQUQ6AEISzAI#v=onepage&q=toaffine%20ecc&f=false) by Diana Maimut, C´edric Murdica, David Naccache and  Mehdi Tibouchi. Pdf

### wNafs
* [wNAF*, an Efficient Left-to-Right Signed Digit Recoding Algorithm](https://link.springer.com/chapter/10.1007/978-3-540-68914-0_26) by Brian King
* [Signed Binary Representations Revisited](https://www.iacr.org/archive/crypto2004/31520122/crypto04_camready2.pdf) by Katsuyuki Okeya, Katja Schmidt-Samoa, Christian Spahn, and Tsuyoshi Takagi

#### Ideas
* [DNS Curves](https://dnscurve.org/index.html)

#### EC255219
* [Curve25519: new Diffie-Hellman speed records](https://cr.yp.to/ecdh/curve25519-20060209.pdf) by Daniel J. Bernstein
* [A state-of-the-art Diffie-Hellman function](https://cr.yp.to/ecdh.html#curve25519-paper) by Daniel J. Bernstein
* [Usage](https://ianix.com/pub/curve25519-deployment.html)
* [A state-of-the-art Diffie-Hellman function - Code](http://cr.yp.to/ecdh.html) by Daniel J. Bernstein
* [Benchmark](http://bench.cr.yp.to/impl-scalarmult/curve25519.html)
* [Toy implementatio](https://sourceforge.net/p/strobe/code/ci/master/tree/x25519.c)

### Edwards Curve
* [Twist Insecurity](http://eprint.iacr.org/2015/577.pdf) by Manfred Lochter and Andreas Wiemers
* [Faster Addition and Doubling on Elliptic Curves](http://download.springer.com/static/pdf/846/chp%253A10.1007%252F978-3-540-76900-2_3.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Fchapter%2F10.1007%2F978-3-540-76900-2_3&token2=exp=1483841050~acl=%2Fstatic%2Fpdf%2F846%2Fchp%25253A10.1007%25252F978-3-540-76900-2_3.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Fchapter%252F10.1007%252F978-3-540-76900-2_3*~hmac=06e0fd268cf19d93fc5ef5f63da7b76ee9a37f84e1700968eed20c8142f77f04) by Daniel J. Bernstein and Tanja Lange.
* [Twisted Edwards Curves](https://eprint.iacr.org/2008/013.pdf) by Daniel J. Bernstein, Peter Birkner, Marc Joye, Tanja Lange, and Christiane Peters
* [Twisted Edwards Curves Revisited](http://iacr.org/archive/asiacrypt2008/53500329/53500329.pdf) by Huseyin Hisil, Kenneth Koon-Ho Wong, Gary Carter, and Ed Dawson.
* [On isogeny classes of Edwards curves over finite fields](https://eprint.iacr.org/2011/135.pdf) by Omran Ahmadi and Robert Granger

#### Theory

#### Encoding
* [Deterministic Encoding into Twisted Edwards Curves](https://www.researchgate.net/publication/304621009_Deterministic_Encoding_into_Twisted_Edwards_Curves) by Wei Yu, Kunpeng Wang, Bao Li and Song Tian.

#### ed448

* [Ed448-Goldilocks](http://ed448goldilocks.sourceforge.net/) by sourceforge.
* [Mike Hamburg Implementation](https://sourceforge.net/p/ed448goldilocks/code/ci/decaf/tree/).
* [STRIKE implementation](https://github.com/twstrike/ed448).
* [Ed448-Goldilocks, a new elliptic curve](https://eprint.iacr.org/2015/625.pdf) by Mike Hamburg.
* [Ed448-Goldilocks, a new elliptic curve](http://eprint.iacr.org/2015/625) by Cryptology ePrint Archive
* [Decaf: Eliminating cofactors through point compression](https://eprint.iacr.org/2015/673.pdf) by Mike Hamburg
* [Implementation on C, on github](https://github.com/coruus/ed448-goldilocks/tree/decaf/include)
* [Fast and compact elliptic-curve cryptography](https://shiftleft.org/papers/fff/fff.pdf) by Mike Hamburg
* [Ed448-Goldilocks, a new elliptic curve](http://csrc.nist.gov/groups/ST/ecc-workshop-2015/papers/session7-hamburg-michael.pdf) by Mike Hamburg
* [Some simple ECC tricks](https://www.math.u-bordeaux.fr/~aenge/ecc2015/documents/hamburg.pdf) by Mike Hamburg
* [Spec](http://ed448goldilocks.sourceforge.net/spec/) by Mike Hamburg

#### elligator
* [Mike Hamburg's explanation](https://moderncrypto.org/mail-archive/curves/2015/000424.html)
* [Elligator: Elliptic-curve points indistinguishable from uniform random strings](http://elligator.cr.yp.to/elligator-20130828.pdf) by Daniel J. Bernstein, Mike Hamburg, Anna Krasnova and Tanja Lange
* [Implementing Elligator for Curve25519](https://www.imperialviolet.org/2013/12/25/elligator.html) by Adam Langley
* [Implementation](https://github.com/Kleshni/Elligator-2) by Kleshni.

#### ed225519
* [Implementation](https://ed25519.cr.yp.to/python/ed25519.py) by Daniel J. Bernstein.
* [Donna-edition](https://github.com/agl/curve25519-donna) by Adam Langley

#### Attacks
* [New algorithm for the discrete logarithm problem on elliptic curves](http://eprint.iacr.org/2015/310.pdf) by Igor Semaev.

#### BenchMarking
* [eBACS: ECRYPT Benchmarking of Cryptographic Systems: SUPERCOP](http://bench.cr.yp.to/supercop.html)

#### extra
* [Hierarchical Deterministic keys over non-linear Keyspace](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2016/blob/master/topics-and-advance-readings/HDKeys-Ed25519.pdf) by Khovratovich and Law

## Hash Functions
* [Cryptographic Hash-Function Basics: Definitions, Implications, and Separations for Preimage Resistance, Second-Preimage Resistance, and Collision Resistance](http://web.cs.ucdavis.edu/~rogaway/papers/relates.pdf) by P. Rogaway and T. Shrimpton
* [The Sponge Functions Corner](http://sponge.noekeon.org/) by Guido Bertoni, Joan Daemen, Michaël Peeters and Gilles Van Assche
* [The Keccak SHA-3 submission](http://keccak.noekeon.org/Keccak-submission-3.pdf) by by Guido Bertoni, Joan Daemen, Michaël Peeters and Gilles Van Assche
* [Stribog](https://github.com/okazymyrov/stribog)
* [FIPS 202 and KeccakDerived Functions](http://csrc.nist.gov/news_events/cif_2015/research/day1_research_200-250pt1.pdf) by John Kelsey

## Random Number Generators
* [Recommendation for Random Number Generation Using Deterministic Random Bit Generators](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-90Ar1.pdf) by NIST
* [Random number generation: An illustrated primer](https://blog.cryptographyengineering.com/2012/02/21/random-number-generation-illustrated/) by Matthew Green
* [Surviving a bad RNG](https://blog.cryptographyengineering.com/2012/03/09/surviving-bad-rng/) by Matthew Green
* [Computational Alternatives to Random Number Generators](http://www.di.ens.fr/~pointche/Documents/Papers/1998_sac.pdf) by David M’Raıhi, David Naccache, David Pointcheval, and Serge Vaudenay

## Message Authentification Code (MAC)
* [SHA3-based MACs](http://csrc.nist.gov/groups/ST/hash/sha-3/Aug2014/documents/perlner_kmac.pdf) by Ray Perlner.
* [New Proofs for NMAC and HMAC: Security without Collision-Resistance](http://cseweb.ucsd.edu/~mihir/papers/hmac-new.pdf) by Mihir Bellare.

### Key derivation functions
* [Key derivation functions](https://cryptography.io/en/latest/hazmat/primitives/key-derivation-functions/) by cryptography.io.
* [Recommendation for Key Derivation Using Pseudorandom Functions](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-108.pdf) by Lily Chen in NIST.

## Digital Signatures
* [New variant of Guillou-Quisquater digital signature scheme](http://www.ijaamm.com/uploads/2/1/4/8/21481830/v3n1p13-92-97.pdf) by J. Ettanfouhi, O. Khadir
* [RSA signatures and Rabin–Williams signatures: the state of the art](https://cr.yp.to/sigs/rwsota-20080131.pdf) by Daniel J. Bernstein.
* [Proving tight security for Rabin–Williams signatures](https://cr.yp.to/sigs/rwtight-20080201.pdf) by Daniel J. Bernstein.
* [Short signatures from the Weil pairing](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf) by Dan Boneh, Ben Lynn, and Hovav Shacham.
* [A Provably Secure Nyberg-Rueppel Signature Variant with Applications](https://eprint.iacr.org/2004/093.pdf) by Giuseppe Ateniese and Breno de Medeiros.
* [Performance of Batch-based Digital Signatures](http://bourbon.usc.edu/iml/bistro/papers/mascots2k2-pub.pdf) by William C. Cheng, Cheng-Fu Chou and Leana Golubchik

### Schnorr signatures
* [Schnorr Signatures: An Overview](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/topics-and-advance-readings/Schnorr-Signatures--An-Overview.md) by Christopher Allen.
* [Multi-user Schnorr security, revisited](https://ed25519.cr.yp.to/multischnorr-20151012.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [Fast and compact elliptic-curve cryptography](https://eprint.iacr.org/2012/309.pdf) by Mike Hamburg

### EdDSA
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-05): The elliptic curve signature scheme Edwards-curve Digital Signature Algorithm (EdDSA) is described by S. Josefsson.
* [Ed25519 and Ed448 for DNSSEC](https://tools.ietf.org/id/draft-sury-dnskey-ed25519-02.xml) by O. Sury
* [EdDSA notes](http://lukas-prokop.at/proj/eddsa/)
* [High-speed high-security signatures](https://ed25519.cr.yp.to/ed25519-20110705.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [EdDSA for more curves](https://ed25519.cr.yp.to/eddsa-20150704.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [The Elliptic Curve Digital Signature Algorithm (ECDSA)](https://www.security-audit.com/files/x9-62-09-20-98.pdf) by American National Standards
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-08) by S. Josefsson and I. Liusvaara

### XEdDSA
* [The XEdDSA and VXEdDSA Signature Schemes](https://whispersystems.org/docs/specifications/xeddsa/#curve448) by Trevor Perrin.

## Validations
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/publications/nistpubs/800-56A/SP800-56A_Revision1_Mar08-2007.pdf) by NIST

## Models

### The Random Oracle Model
* [The random oracle model: a twenty-year retrospective](https://eprint.iacr.org/2015/140.pdf) by Neal Koblitz and Alfred J. Menezes.

## Protocol

### Sociallist Millionaire Protocol (SMP)
* [Socialist Millionaire Protocol Passphrase Generator](https://github.com/dillbyrne/smpp-generator) by dillbyrne.

### Double Ratchet
* [The Double Ratchet Algorithm](https://whispersystems.org/docs/specifications/doubleratchet/) by Trevor Perrin (editor) and Moxie Marlinspike.

### STROBE
* [The Strobe Protocol](http://eprint.iacr.org/2017/003.pdf) by Mike Hamburg

## Schemes

* [Folklore, Practice and Theory of Robust Combiners](http://eprint.iacr.org/2002/135.pdf) by Amir Herzberg.

## Security

* [Chosen-Ciphertext Security of Multiple Encryption](https://www.cs.nyu.edu/~dodis/ps/2enc.pdf) by Yevgeniy Dodis and Jonathan Katz.
* [Encryption Works](https://github.com/freedomofpress/encryption-works/blob/master/original/encryption_works.pdf) by FOPsF
* [Project Wycheproof](https://github.com/google/wycheproof)

## Compendia
* [Theory of Cryptography: 9th Theory of Cryptography Conference, TCC 2012](https://books.google.com.ec/books?id=iWirCAAAQBAJ&pg=PA223&lpg=PA223&dq=malleable+symmetric+schemes&source=bl&ots=3oszTtlOhU&sig=evzVsQk3DbLMdkZLVY_O6RD5BfQ&hl=en&sa=X&ved=0ahUKEwjrh4XU2rPPAhUFox4KHY-UAS0Q6AEIKjAD#v=onepage&q=malleable%20symmetric%20schemes&f=false), edited by Ronald Cramer.
* [Recommendation for Key Management](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) by Elaine Barker in NIST.
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/groups/ST/toolkit/documents/SP800-56Arev1_3-8-07.pdf) by Elaine Barker, Don Johnson, and Miles Smid in NIST.

## Library

### Pairing-based cryptography
* [The PBC (Pairing-Based Cryptography) library](https://crypto.stanford.edu/pbc/) by Ben Lynn.

### Nik Unger otr implementation
* [Off-the-Record Messaging](https://crysp.uwaterloo.ca/software/) by Ian Goldberg.

### General
* [Crypto++ 5.6.5](https://www.cryptopp.com/release565.html)
* [cryptopp](https://github.com/weidai11/cryptopp)
* [The Apache Milagro Cryptographic Library](https://github.com/MIRACL/amcl)
* [DeDiS Advanced Crypto Library for Go](https://github.com/dedis/crypto)

### Javascript
* [Stanford Javascript Crypto Library](http://bitwiseshiftleft.github.io/sjcl/)

## PostQuantum Crypto
* [PQCHacks: A gentle introduction to post-quantum cryptography](https://media.ccc.de/v/32c3-7210-pqchacks#video&t=908) by djb and Tanja Lange in 32c3.
* [Towards quantum-resistance cryptosystems from supersingular elliptic curve isogenies](http://eprint.iacr.org/2011/506.pdf) by Luca de Feo, David Jao and Jerome Plut.
* [Quantum computers are coming!](https://www.youtube.com/watch?v=c7OHv-L-x50) by Tanja Lange and Daniel J. Bernstein
* [Ring learning with errors](https://en.wikipedia.org/wiki/Ring_learning_with_errors)

## Mailing List
* [Modern Crypto](https://moderncrypto.org/mail-archive/)
* [The Internet Engineering Task Force -IETF-](https://www.ietf.org/mail-archive/web/cfrg/current/maillist.html)
* [Cypherpunks](https://lists.cypherpunks.ca/pipermail)

## Hacking (in general)
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)

## Various
* [Rebooting the Web-of-Trust](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust)
* [Tor Browser Bundle - iSEC Deliverable 1.3](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf)
