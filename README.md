# Useful Crypto-related Resources

## General
* [Non-Malleable Cryptography](https://www.cs.huji.ac.il/~dolev/pubs/nmc.pdf)
by Danny Dolev, Cynthia Dwork, Moni Naor
* [The Uneasy Relationship Between Mathematics and Cryptography](https://www.ams.org/notices/200708/tx070800972p.pdf) by Neal Koblitz
* [Another Look at “Provable Security”](https://eprint.iacr.org/2004/152.pdf) by Neal Koblitz and Alfred J. Menezes

## Authenticated Encryption

* [Challenges in Authenticated Encryption](https://chae.cr.yp.to/chae-20170301.pdf) by Daniel J. Bernstein
* [Boosting Authenticated Encryption Robustness With Minimal Modifications](https://eprint.iacr.org/2017/239.pdf) by Tomer Ashur, Orr Dunkelman
, and Atul Luykx

## AKE
* [An Efficient Protocol for Authenticated Key Agreement](http://cacr.uwaterloo.ca/techreports/1998/corr98-05.pdf) by Laurie Law, Alfred Menezes, Minghua Qu, Jerry Solinas.
* [Two-party authenticated key exchange protocol using lattice-based cryptography](https://eprint.iacr.org/2016/761.pdf) by Xiaopeng Yang and Wenping Ma
* [The X3DH Key Agreement Protocol](https://whispersystems.org/docs/specifications/x3dh/x3dh.pdf) by Moxie Marlinspike and Trevor Perrin
* [Deniable Authentication and Key Exchange](https://eprint.iacr.org/2006/280.ps) by Mario Di Raimondo, Rosario Gennaro and Hugo Krawczyk
* [A non-interactive deniable authentication scheme in the standard model](https://pdfs.semanticscholar.org/61bb/605cba4226c15b2733e6e8ee22d900a9200b.pdf?_ga=2.69522008.931186499.1496171578-1355135719.1496171572) by Bin Wang, Qing Zhao and Ke Dai
* [A non-interactive deniable authentication scheme in the standard model](https://www.semanticscholar.org/paper/A-non-interactive-deniable-authentication-scheme-i-Wang-Zhao/61bb605cba4226c15b2733e6e8ee22d900a9200b) by Bin Wang, Qing Zhao and Ke Dai
* [Authenticated Key Exchange from Ideal Lattices](https://eprint.iacr.org/2014/589.pdf) by Jiang Zhang, Zhenfeng Zhang, Jintai Ding, Michael Snook, and Ozgür Dagdelen

## Network Protocols

* [Security Analysis of Network Protocols](http://web.stanford.edu/class/cs259/WWW08/slides/01-Introduction.pdf) by John Mitchell

### TLS

* [Encrypting the Internet with Go](https://www.youtube.com/watch?v=CB_VfgwPmxQ) by Filippo Valsorda
* [SSL and HTTPS](https://www.youtube.com/watch?v=S2iBR2ZlZf0) by Nickolai Zeldovich and their [notes](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/lecture-notes/MIT6_858F14_lec14.pdf)
* [The New Illustrated TLS Connection](https://tls13.ulfheim.net/)
* [TLS Handshake : Under The Hood](https://medium.com/@technospace/tls-handshake-under-the-hood-79d20c0020de#) by Sathya Bandara

## OTR

### OTRv2

* [Finite-State Security Analysis of OTR Version 2](http://www.jbonneau.com/doc/BM06-OTR_v2_analysis.pdf) by Joseph Bonneau and Andrew Morrison.
* [Protocol](https://otr.cypherpunks.ca/Protocol-2.0.2.txt) by Nikita Borisov and Ian Goldberg.
* [Secure Off-the-Record Messaging](https://www.dmi.unict.it/diraimondo/web/wp-content/uploads/papers/otr.pdf) by Mario Di Raimondo, Rosario Gennaro and Hugo Krawczyk

### OTRv3
* [Timeframe](https://bugs.otr.im/lib/libotr/blob/master/src/message.h#L259)

### Multiparty
* [Multi-party Off-the-Record Messaging](https://www.cypherpunks.ca/~iang/pubs/mpotr.pdf) by Ian Golberg et Al.
* [Improved Group Off-the-Record Messaging](https://www-users.cs.umn.edu/~hoppernj/gotr.pdf) by Hong Liu, Eugene Y. Vasserman and Nicholas Hopper
* [Improved Deniable Signature Key Exchange for mpOTR](https://matt.singlethink.net/projects/mpotr/improved-dske.pdf) by Matthew Van Gundy

### Usability
* [Improved User Authentication in Off-The-Record Messaging](http://www.cypherpunks.ca/~iang/pubs/impauth.pdf) by Chris Alexander and Ian Goldberg
* [A User Study of Off-the-Record Messaging](http://www.cypherpunks.ca/~iang/pubs/otr_userstudy.pdf) by Ryan Stedman, Kayo Yoshida and Ian Goldberg

## Signal Protocol

* [A Formal Security Analysis of the Signal Messaging Protocol](https://eprint.iacr.org/2016/1013.pdf) by Katriel Cohn-Gordon, Cas Cremers, Benjamin Dowling, Luke Garratt and Douglas Stebila.
* [How Secure is TextSecure?](https://eprint.iacr.org/2014/904.pdf) by Tilman Frosch, Christian Mainka, Christoph Bader, Florian Bergsma, Jorg Schwenk and Thorsten Holz.
* [Technology preview: Private contact discovery for Signal](https://signal.org/blog/private-contact-discovery/)
* [Is Bob Sending Mixed Signals?](https://www-users.cs.umn.edu/~hoppernj/mixed_signals_wpes17.pdf) by Michael Schliep, Ian Kariniemi and Nicholas Hopper.


## Zero Knowledge Proof
* [Multiple Non-Interactive Zero Knowledge Proofs Based on a Single Random String](https://www.computer.org/csdl/proceedings/focs/1990/2082/00/089549.pdf) by Uriel Feige, Dror Lapidot and Adi Shamir.

## Ciphers

* [So you want to use an alternative cipher…](https://blog.cryptographyengineering.com/2012/10/09/so-you-want-to-use-alternative-cipher/) by Matthew Green.
* [Why switch from AES to a new stream cipher?](https://cr.yp.to/streamciphers/why.html) by Daniel Bernstein.

### Stream cipher

#### Nonce
* [Introducing Miscreant: a multi-language misuse resistant encryption library](https://tonyarcieri.com/introducing-miscreant-a-multi-language-misuse-resistant-encryption-library) by Tony Arceri
* [Nonce misuse resistance 101](https://www.lvh.io/posts/nonce-misuse-resistance-101.html) by lvh
* [Online Authenticated-Encryption and its Nonce-Reuse Misuse-Resistance](http://web.cs.ucdavis.edu/~rogaway/papers/oae.pdf) by Viet Tung Hoang, Reza Reyhanitabar, Phillip Rogaway and Damian Vizár

#### AES
* [Another New AES Attack](https://www.schneier.com/blog/archives/2009/07/another_new_aes.html) by Bruce Schneier

#### Salsa 20
* [Salsa20 security](https://cr.yp.to/snuffle/security.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.
* [Notes](https://cr.yp.to/snuffle.html)

#### XSalsa20
* [Extending the Salsa20 nonce](http://cr.yp.to/snuffle/xsalsa-20081128.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.
* [Implementation](https://github.com/golang/crypto/blob/master/nacl/secretbox/secretbox.go) in NaCl

#### ChaCha20
* [ChaCha20 and Poly1305 for IETF Protocols](https://tools.ietf.org/html/rfc7539) by Y. Nir and A. Langley
* [ChaCha20-Poly1305 Cipher Suites for Transport Layer Security (TLS)](https://tools.ietf.org/html/draft-ietf-tls-chacha20-poly1305-04) by A. Langley, W. Chang,  N. Mavrogiannopoulos, J. Strombergson and S. Josefsson

#### Analysis of Salsa, ChaCha and Rumba

* [New Features of Latin Dances: Analysis of Salsa, ChaCha, and Rumba](http://cr.yp.to/rumba20/newfeatures-20071218.pdf) by Jean-Philippe Aumasson, Simon Fischer, Shahram Khazaei, Willi Meier, and Christian Rechberger
* [Improved Key Recovery Attacks on Reduced-Round Salsa20 and ChaCha](https://link.springer.com/chapter/10.1007/978-3-642-37682-5_24) by Zhenqing Shi, Bin Zhang, Dengguo Feng and Wenling Wu

### Blockcipher

#### In general
* [Evaluation of Some Blockcipher Modes of Operation](http://web.cs.ucdavis.edu/~rogaway/papers/modes.pdf) by Phillip Rogaway.

## Symmetric key algorithm

### DES
* [On the Security of Multiple Encryption](http://cs.jhu.edu/~sdoshi/crypto/papers/p465-merkle.pdf) by Ralph C. Merkle and Martin E. Hellman

## Key Exchange

### Theory
* [Entity Authentication and Key Distribution](https://cseweb.ucsd.edu/~mihir/papers/eakd.pdf) by Mihir Bellare and Phillip Rogaway
* [Key Agreement Protocols and their Security Analysis](https://pdfs.semanticscholar.org/fdb0/3a4a533e09b71b18045ba85ba9978de65a2d.pdf) by Simon Blake-Wilson, Don Johnson and Alfred Menezes.

### With Anonymous Authentication
* [Key Exchange with Anonymous Authentication using DAA-SIGMA Protocol](https://eprint.iacr.org/2010/454.pdf) by Jesse Walker and Jiangtao Li

### Degenerate
* [Degenerate Keys for RSA Encryption](https://pdfs.semanticscholar.org/2a2e/6585b83949cc13e58444f7b4435cf76d2920.pdf) by Seth D. Bergmann
* [Info](https://books.google.de/books?id=amW5BQAAQBAJ&pg=PA205&lpg=PA205&dq=check+for+degenerate+key+crypto&source=bl&ots=IChUHyW5O8&sig=WC1JF6QumuLoX_k9lnql_5Aee8c&hl=es-419&sa=X&sqi=2&ved=0ahUKEwjQybzEsZDSAhVnwYMKHfjFDHsQ6AEILDAC#v=onepage&q=check%20for%20degenerate%20key%20crypto&f=false)
* [Degenerate Curve Attacks](https://eprint.iacr.org/2015/1233.pdf) by Samuel Neves and Mehdi Tibouchi

### Fault Attacks
* [Fault-resistant calculcations on elliptic curves](https://www.google.com/patents/US8457303) by Marc Joye

### Diffie Hellman
* [New directions in Cryptography](https://www-ee.stanford.edu/~hellman/publications/24.pdf) by Diffie and Hellman.
* [Diffie-Hellman key exchange](http://www.math.ucla.edu/~baker/40/handouts/rev_DH/node1.html) by Nikos Drakos
* [Diffie-Hellman Key Agreement Method](https://www.ietf.org/rfc/rfc2631.txt) by E. Rescorla
* [Diffie-Hellman parameters](https://wiki.openssl.org/index.php/Diffie-Hellman_parameters) by OpenSSL
* [Imperfect Forward Secrecy: How Diffie-Hellman Fails in Practice](https://weakdh.org/imperfect-forward-secrecy-ccs15.pdf) by David Adrian et al
* [Diffie-hellman](https://www.cryptopp.com/wiki/Diffie-hellman#Key_Agreement_and_Transport) by Crypto++
* [Public key parameters](http://cacr.uwaterloo.ca/hac/about/chap4.pdf#page=164)
* [A One Round Protocol for Tripartite Diffie–Hellman](https://pdfs.semanticscholar.org/845e/96c20e5a5ff3b03f4caf72c3cb817a7fa542.pdf) by Antoine Joux
* [The Decision Diffie-Hellman Problem](http://crypto.stanford.edu/~dabo/pubs/papers/DDH.pdf) by Dan Boneh
* [On Diffie-Hellman key agreement with short exponents](https://www.google.com.ec/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwitwcqf_ObVAhVE5iYKHZ3VA0IQFggkMAA&url=https%3A%2F%2Fpdfs.semanticscholar.org%2F2b39%2F13d1dfcb1dc90463a37edfe606922f093e97.pdf&usg=AFQjCNEm-aBpKhd81J4NHqA81MLS0DOK9g) by P. C. van Oorschot and M. J. Wiener
* [Diffie-Hellman Key Agreement Method](https://tools.ietf.org/html/rfc2631) by E. Rescorla
* [Additional Diffie-Hellman Groups for Use with IETF Standards](https://tools.ietf.org/html/rfc5114) by M. Lepinski and S. Kent
* [HMQV: A High-Performance Secure Diffie-Hellman Protocol](https://eprint.iacr.org/2005/176.pdf) by Hugo Krawczyk
* [More Modular Exponential (MODP) Diffie-Hellman groups for Internet Key Exchange (IKE)](https://www.ietf.org/rfc/rfc3526.txt) by T. Kivinen and M. Kojo
* [IEEE Standard Specifications for Public-Key Cryptography](https://perso.telecom-paristech.fr/guilley/recherche/cryptoprocesseurs/ieee/00891000.pdf)

#### Validation
* [Additional Diffie-Hellman Tests for the Internet Key Exchange Protocol Version 2](https://tools.ietf.org/html/rfc6989#section-2.1) by Y. Sheffer Porticor, S. Fluhrer
* [Methods for Avoiding the "Small-Subgroup" Attacks on the Diffie-Hellman Key Agreement Method for S/MIME](https://tools.ietf.org/html/rfc2785) by R. Zuccherato

#### Attacks
* [Timing Attacks on Implementations of Diffie-Hellman, RSA, DSS, and Other Systems](https://42xtjqm0qj0382ac91ye9exr-wpengine.netdna-ssl.com/wp-content/uploads/2015/08/TimingAttacks.pdf) by Paul C. Kocher
* [On reusing ephemeral keys in Diffie-Hellman key agreement protocols](http://cacr.uwaterloo.ca/techreports/2008/cacr2008-24.pdf) by Alfred Menezes and Berkant Ustaoglu
* [A lesson in timing attacks](https://codahale.com/a-lesson-in-timing-attacks/) by codahale
* [Measuring small subgroup attacks against Diffie-Hellman](https://eprint.iacr.org/2016/995.pdf) by Luke Valenta, David Adrian, Antonio Sanso, Shaanan Cohney, Joshua Fried, Marcella Hastings, J. Alex Halderman and Nadia Heninger. [Slides](https://www.seas.upenn.edu/~lukev/files/subgroup-slides.pdf)
* [Remote Timing Attacks are Practical](http://crypto.stanford.edu/~dabo/pubs/papers/ssl-timing.pdf) by David Brumley and Dan Boneh
* [Why Constant-Time Crypto?](https://www.bearssl.org/constanttime.html)

### Cramer-Shoup
* [Cramer Shoup Cryto-System Java implementation](https://github.com/omoeller/cramshou) by omoeller (not audited).
* [Cramer Shoup Cryto-System Python implementation](https://github.com/benkreuter/cca2python) by benkreuter.

### ElGamal
* [A Public Key Cryptosystem and a Signature Scheme Based on Discrete Logarithms](http://caislab.kaist.ac.kr/lecture/2010/spring/cs548/basic/B02.pdf) by Taher ElGamal
* [ElGamal:Public-Key Cryptosystem](http://cs.indstate.edu/~jgrewal/steps.pdf) by Jaspreet Kaur Grewal

### Dual Receiver Encryption
* [The Dual Receiver Cryptosystem and Its Applications](https://www.cs.columbia.edu/~angelos/Papers/combo.pdf) by Theodore Diament, Homin K. Lee, Angelos D. Keromytis and Moti Yung
* [Practical Dual-Receiver Encryption Soundness, Complete Non-Malleability, and Applications](https://eprint.iacr.org/2013/858.pdf) by Sherman S.M. Chow, Matthew Franklin, and Haibin Zhang

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
* [Rigid Parameter Generation for Elliptic Curve Cryptography](https://tools.ietf.org/html/draft-black-rpgecc-01#page-6) by B. Black, J. Bos, C. Costello, A. Langley, P. Longa and M. Naehrig
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
* [A Las Vegas algorithm to solve the elliptic curve discrete logarithm problem](https://arxiv.org/pdf/1703.07544.pdf) by Ayan Mahalanobis and Vivek Mallick
* [On isogeny classes of Edwards curves over finite fields](http://www.sciencedirect.com/science/article/pii/S0022314X1200025X) by Omran Ahmadi and
Robert Granger
* [Explicit-Formulas Database](https://hyperelliptic.org/EFD/) by Tanja Lange
* [Validation of Elliptic Curve Public Keys](https://www.iacr.org/archive/pkc2003/25670211/25670211.pdf) by Adrian Antipa, Daniel Brown, Alfred Menezes,
René Struik and Scott Vanstone
* [Fast genus 2 arithmetic based on Theta functions](https://eprint.iacr.org/2005/314.ps) by P. Gaudry
* [Point Generation And Base Point Selection In ECC: An Overview](https://www.ijarcce.com/upload/2014/may/IJARCCE7J%20%20a%20moumita%20Point%20Generation%20And%20Base.pdf) by Moumita Roy, Nabamita Deb and Amar Jyoti Kumar
* [Fundamental Elliptic Curve Cryptography Algorithms](https://tools.ietf.org/html/rfc6090#section-8) by D. McGrew, K. Igoe and  M. Salter
* [Elliptic Curve Groups modulo a Prime (ECP Groups) for IKE and IKEv2](https://tools.ietf.org/html/rfc5903) by D. Fu and J. Solinas
* [Elliptic Curve Cryptography in Practice](https://eprint.iacr.org/2013/734.pdf) by Joppe W. Bos, J. Alex Halderman, Nadia Heninger, Jonathan Moore, Michael Naehrig and Eric Wustrow
* [Why Ellipses Are Not Elliptic Curves](https://www.maa.org/sites/default/files/pdf/upload_library/2/Rice-2013.pdf) by Adrian Rice and Ezra Brown
* [Visualization](http://ecc.iteg.at/) by Wolfgang Glas
* [Elliptic Curves, Group Law, and Efficient Computation](https://core.ac.uk/download/pdf/10898289.pdf) by Hüseyin Hisil. The
  [presentation](https://www.ucc.ie/en/media/academic/centreforplanningeducationresearch/EDawson.pdf)
* [Some notes](https://crypto.stanford.edu/pbc/notes/elliptic/group.html) by Benn Lynn
* [SEC 1: Elliptic Curve Cryptography](http://www.secg.org/sec1-v2.pdf) by Daniel R. L. Brown
* [BLS signatures, hashing to curves, and more dispatches from the IETF](https://www.youtube.com/watch?v=5HB8QBoBv98)
* [Sage](http://blog.bjrn.se/2015/07/lets-construct-elliptic-curve.html)
* [The Jacobi Model of an Elliptic Curve and Side-Channel Analysis])https://eprint.iacr.org/2002/125.pdf) by Olivier Billet and Marc Joye

#### Encoding
* [Rational points on certain hyperelliptic curves over finite fields](https://arxiv.org/pdf/0706.1448.pdf) by Maciej Ulas
* [Construction of Rational Points on Elliptic Curves over Finite Fields](https://pdfs.semanticscholar.org/8986/08930ce6485a61f2f37977fc7f6420093710.pdf) by Andrew Shallue and Christiaan E. van de Woestijne
* [Compression and decompression of elliptic curve data points](https://patents.google.com/patent/US6252960)
* [Encoding points in hyperelliptic curves over finite fields in deterministic polynomial time](https://arxiv.org/pdf/1005.1454.pdf) by Jean-Gabriel Kammerer, Reynald Lercier, and Guénaël Renault

#### Twist
* [Twist Insecurity](http://eprint.iacr.org/2015/577.pdf) by Manfred Lochter and Andreas Wiemers
* [Twist security](http://safecurves.cr.yp.to/twist.html)

#### Jacobic
* [The Jacobi Model of an Elliptic Curve and Side-Channel Analysis](https://eprint.iacr.org/2002/125.pdf) by Olivier Billet and Marc Joye

#### Kummer varieties
* [Arithmetic on Abelian and Kummer Varieties](https://eprint.iacr.org/2014/493.pdf) by David Lubicz And Damien Robert

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
* [Elliptic vs. hyperelliptic](https://cr.yp.to/talks/2006.09.20/slides.pdf) by Daniel Bernstein
* [Operations](http://www.hyperelliptic.org/EFD/g1p/auto-edwards-projective.html#addition-add-2007-bl) by Tanja Lange

#### Courses
* [MIT course](https://ocw.mit.edu/courses/mathematics/18-783-elliptic-curves-spring-2017/lecture-notes/)

#### Conversions
* [Fault Attacks on Projective-to-Affine Coordinates Conversion](https://cosade.telecom-paristech.fr/cosade13/presentations/session2_b.pdf) by Diana Maimut, C´edric Murdica, David Naccache and  Mehdi Tibouchi. Presentation
* [Fault Attacks on Projective-to-Affine Coordinates Conversion](https://books.google.com.ec/books?id=c_y5BQAAQBAJ&pg=PA46&lpg=PA46&dq=toaffine+ecc&source=bl&ots=twi-3g-Ea7&sig=UWNbVQLkW-DSKAk0E2Bw-bG5I4s&hl=en&sa=X&ved=0ahUKEwjajLqVh6LSAhUp04MKHVWZDQUQ6AEISzAI#v=onepage&q=toaffine%20ecc&f=false) by Diana Maimut, C´edric Murdica, David Naccache and  Mehdi Tibouchi. Pdf

### wNafs
* [wNAF\*, an Efficient Left-to-Right Signed Digit Recoding Algorithm](https://link.springer.com/chapter/10.1007/978-3-540-68914-0_26) by Brian King
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
* [High-speed Curve25519 on 8-bit, 16-bit, and 32-bit microcontrollers](http://eprint.iacr.org/2015/343.pdf) by Michael Düll, Björn Haase, Gesine Hinterwälder, Michael Hutter, Christof Paar and Ana Helena Sánchez
* [May the Fourth Be With You: A Microarchitectural Side Channel
Attack on Several Real-World Applications of Curve25519](https://eprint.iacr.org/2017/806.pdf) by Daniel Genkin, Luke Valenta and Yuval Yarom

### Edwards Curve
* [Twist Insecurity](http://eprint.iacr.org/2015/577.pdf) by Manfred Lochter and Andreas Wiemers
* [Faster Addition and Doubling on Elliptic Curves](http://download.springer.com/static/pdf/846/chp%253A10.1007%252F978-3-540-76900-2_3.pdf?originUrl=http%3A%2F%2Flink.springer.com%2Fchapter%2F10.1007%2F978-3-540-76900-2_3&token2=exp=1483841050~acl=%2Fstatic%2Fpdf%2F846%2Fchp%25253A10.1007%25252F978-3-540-76900-2_3.pdf%3ForiginUrl%3Dhttp%253A%252F%252Flink.springer.com%252Fchapter%252F10.1007%252F978-3-540-76900-2_3*~hmac=06e0fd268cf19d93fc5ef5f63da7b76ee9a37f84e1700968eed20c8142f77f04) by Daniel J. Bernstein and Tanja Lange.
* [Twisted Edwards Curves](https://eprint.iacr.org/2008/013.pdf) by Daniel J. Bernstein, Peter Birkner, Marc Joye, Tanja Lange, and Christiane Peters
* [Twisted Edwards Curves Revisited](http://iacr.org/archive/asiacrypt2008/53500329/53500329.pdf) by Huseyin Hisil, Kenneth Koon-Ho Wong, Gary Carter, and Ed Dawson.
* [On isogeny classes of Edwards curves over finite fields](https://eprint.iacr.org/2011/135.pdf) by Omran Ahmadi and Robert Granger
* [Collective Edwards-Curve Digital Signature Algorithm](https://datatracker.ietf.org/doc/draft-ford-cfrg-cosi/)
* [Multiquadratics](https://multiquad.cr.yp.to/software.html)

### X448
* [Implementation](https://git.schwanenlied.me/yawning/x448)

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
* [SHA-3 Derived Functions: cSHAKE, KMAC, TupleHash and ParallelHash](http://csrc.nist.gov/publications/drafts/800-185/sp800_185_draft.pdf) by NIST
* [A new Design Criteria for Hash-Functions](http://www.cs.nyu.edu/~puniya/papers/nist.pdf) by Jean-Sebastien Coron, Yevgeniy Dodis, , Cecile Malinaud, and Prashant Puniya
* [BLAKE2: simpler, smaller, fast as MD5](https://eprint.iacr.org/2013/322.pdf) by Jean-Philippe Aumasson, Samuel Neves, Zooko Wilcox-O’Hearn and Christian Winnerlein
* [Analysis of BLAKE2](https://eprint.iacr.org/2013/467.pdf) by Jian Guo,
Pierre Karpman, Ivica Nikolic, Lei Wang and Shuang Wu
* [BLAKE2: “Harder, Better, Faster, Stronger” Than MD5](https://leastauthority.com/blog/BLAKE2-harder-better-faster-stronger-than-MD5/) by  Zooko Wilcox-O'Hearn
* [BLAKE 2: slides](https://blake2.net/acns/slides.html)
* [BLAKE2 — fast secure hashing](https://blake2.net/)

## Key generation function
* [Argon2](https://en.wikipedia.org/wiki/Argon2)

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
* [How To Prove Yourself: Practical Solutions to Identification and Signature Problems](http://www.math.uni-frankfurt.de/~dmst/teaching/SS2012/Vorlesung/Fiat.Shamir.pdf) by Amos Fiat and Adi Shamir

### Schnorr signatures
* [Schnorr Signatures: An Overview](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/topics-and-advance-readings/Schnorr-Signatures--An-Overview.md) by Christopher Allen.
* [Multi-user Schnorr security, revisited](https://ed25519.cr.yp.to/multischnorr-20151012.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [Fast and compact elliptic-curve cryptography](https://eprint.iacr.org/2012/309.pdf) by Mike Hamburg
* [Efficient Ring Signatures without Random Oracles](https://eprint.iacr.org/2006/289.pdf) by Hovav Shacham and Brent Waters
* [Efficient Signature Generation by Smart Cards](https://www.researchgate.net/profile/Claus_Schnorr/publication/227088517_Efficient_signature_generation_by_smart_cards/links/0046353849579ce09c000000.pdf) by C. P. Schnorr
* [Proofs of Partial Knowledge and Simplified Design of Witness Hiding Protocols](http://www.win.tue.nl/~berry/papers/crypto94.pdf) by Ronald Cramer, Ivan Damgard, Aarhus University and Berry Schoenmakers

### Hash-based signatures
* [SPHINCS: practical stateless hash-based signatures](https://eprint.iacr.org/2014/795.pdf) by Daniel J. Bernstein, Daira Hopwood, Andreas Hülsing, Tanja Lange, Ruben Niederhagen, Louiza Papachristodoulou, Michael Schneider, Peter Schwabe and Zooko Wilcox-O’Hearn

### EdDSA
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-05): The elliptic curve signature scheme Edwards-curve Digital Signature Algorithm (EdDSA) is described by S. Josefsson.
* [Ed25519 and Ed448 for DNSSEC](https://tools.ietf.org/id/draft-sury-dnskey-ed25519-02.xml) by O. Sury
* [EdDSA notes](http://lukas-prokop.at/proj/eddsa/)
* [High-speed high-security signatures](https://ed25519.cr.yp.to/ed25519-20110705.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [EdDSA for more curves](https://ed25519.cr.yp.to/eddsa-20150704.pdf) by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe and Bo-Yin Yang
* [The Elliptic Curve Digital Signature Algorithm (ECDSA)](https://www.security-audit.com/files/x9-62-09-20-98.pdf) by American National Standards
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-08) by S. Josefsson and I. Liusvaara (draft)
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-00) by S. Josefsson and I. Liusvaara (draft)
* [Edwards-Curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/rfc8032) by S. Josefsson and I. Liusvaara
* [Breaking Ed25519 in WolfSSL](https://eprint.iacr.org/2017/985.pdf) by Niels Samwel, Lejla Batina, Guido Bertoni, Joan
Daemen, and Ruggero Susella
* [A Side-Channel Assisted Cryptanalytic AttackAgainst QcBits](https://eprint.iacr.org/2017/596.pdf) by Melissa
Rossi, Mike Hamburg, Michael Hutter and Mark E. Marson
* [EdDSA for more curves](https://eprint.iacr.org/2015/677.pdf) by Daniel J. Bernstein, Simon Josefsson, Tanja Lange, Peter Schwabe and Bo-Yin Yang

### XEdDSA
* [The XEdDSA and VXEdDSA Signature Schemes](https://whispersystems.org/docs/specifications/xeddsa/#curve448) by Trevor Perrin.

### qDSA
* [qDSA: Small and Secure Digital Signatures with Curve-based Diffie–Hellman Key Pairs](http://eprint.iacr.org/2017/518.pdf) by Joost Renes and Benjamin Smith

## Zero-Knowledge
* [Concurrent Zero-Knowledge](http://web.cs.ucla.edu/~sahai/work/web/1998%20Publications/STOC_C.Dwork1998.pdf) by Cynthia Dlvork, Moni Naori and Amit Sahai
* [Efficient and Non-Malleable Proofs of Plaintext Knowledge and Applications](https://www.google.com.ec/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjDsvG--YzVAhUTxCYKHfzIBxcQFggkMAA&url=https%3A%2F%2Flink.springer.com%2Fchapter%2F10.1007%2F3-540-39200-9_13&usg=AFQjCNFE-emSo_CQP1XMWj6kYq5jVXsijw) by Jonathan Katz

## Validations
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/publications/nistpubs/800-56A/SP800-56A_Revision1_Mar08-2007.pdf) by NIST

## Models

### The Random Oracle Model
* [The random oracle model: a twenty-year retrospective](https://eprint.iacr.org/2015/140.pdf) by Neal Koblitz and Alfred J. Menezes.

## Formal Verifications
* [C murphi](http://mclab.di.uniroma1.it/site/index.php/software/18-cmurphi).
* [Formal verification group webpage](http://formalverification.cs.utah.edu/classic/) by the University of Utah (archived)
* [Eddy Murphi](http://formalverification.cs.utah.edu/EddyMurphi/)
* [Murphi Model Checker](http://formalverification.cs.utah.edu/Murphi/index.html)
* [Nik Unger pull request on CMurphi](https://bitbucket.org/mclab/cmurphi/pull-requests/1/make-cmurphi-work-with-modern-optimizing/diff)

## Mix networks

* [Sphinx: A Compact and Provably Secure Mix Format](https://www.cypherpunks.ca/~iang/pubs/Sphinx_Oakland09.pdf) by George Danezis and Ian Goldberg.
* [From a Trickle to a Flood: Active Attacks on Several Mix Types](https://www.freehaven.net/doc/batching-taxonomy/taxonomy.pdf) by Andrei Serjantov, Roger Dingledine and Paul Syverson
* [Heartbeat Traffic to Counter (n-1) Attacks](https://www.freehaven.net/anonbib/cache/danezis:wpes2003.pdf) by George Danezis and Len Sassaman
* [The Loopix Anonymity System](https://arxiv.org/pdf/1703.00536.pdf) by Ania Piotrowska, Jamie Hayes, Tariq Elahi, Sebastian Meiser and George Danezis

## Anonimity

* [Anonymity Trilemma: Strong Anonymity, Low Bandwidth Overhead, Low Latency—Choose Two](https://eprint.iacr.org/2017/954.pdf) by Debajyoti Das, Sebastian Meiser, Esfandiar Mohammadi and Aniket Kate

## Protocol

### Sociallist Millionaire Protocol (SMP)
* [Socialist Millionaire Protocol Passphrase Generator](https://github.com/dillbyrne/smpp-generator) by dillbyrne.
* [A Fair and Efficient Solution to the Socialist Millionaires’ Problem](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.10.3406&rep=rep1&type=pdf) by Fabrice Boudot, Berry Schoenmakers and Jacques Traoré

### Double Ratchet
* [The Double Ratchet Algorithm](https://whispersystems.org/docs/specifications/doubleratchet/) by Trevor Perrin (editor) and Moxie Marlinspike.

### STROBE
* [The Strobe Protocol](http://eprint.iacr.org/2017/003.pdf) by Mike Hamburg

### [The OAKLEY Key Determination Protocol]
* [The OAKLEY Key Determination Protocol](https://tools.ietf.org/html/rfc2412)
by H. Orman

## Schemes

* [Folklore, Practice and Theory of Robust Combiners](http://eprint.iacr.org/2002/135.pdf) by Amir Herzberg.

## Security

* [Chosen-Ciphertext Security of Multiple Encryption](https://www.cs.nyu.edu/~dodis/ps/2enc.pdf) by Yevgeniy Dodis and Jonathan Katz.
* [Encryption Works](https://github.com/freedomofpress/encryption-works/blob/master/original/encryption_works.pdf) by FOPsF
* [Project Wycheproof](https://github.com/google/wycheproof)
* [Universally Composable Security: A New Paradigm for Cryptographic Protocols](https://eprint.iacr.org/2000/067.pdf) by Ran Canetti
* [Security workshop](https://www.youtube.com/watch?v=Qda8plpKDgg) by Dan Boneh

## Compendia
* [Theory of Cryptography: 9th Theory of Cryptography Conference, TCC 2012](https://books.google.com.ec/books?id=iWirCAAAQBAJ&pg=PA223&lpg=PA223&dq=malleable+symmetric+schemes&source=bl&ots=3oszTtlOhU&sig=evzVsQk3DbLMdkZLVY_O6RD5BfQ&hl=en&sa=X&ved=0ahUKEwjrh4XU2rPPAhUFox4KHY-UAS0Q6AEIKjAD#v=onepage&q=malleable%20symmetric%20schemes&f=false), edited by Ronald Cramer.
* [Recommendation for Key Management](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) by Elaine Barker in NIST.
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/groups/ST/toolkit/documents/SP800-56Arev1_3-8-07.pdf) by Elaine Barker, Don Johnson, and Miles Smid in NIST.

## School
* [Workshop on Elliptic Curve Cryptography (ECC)](https://hyperelliptic.org/ECC/index.html)

## Library

### Pairing-based cryptography
* [The PBC (Pairing-Based Cryptography) library](https://crypto.stanford.edu/pbc/) by Ben Lynn.
* [A Practical Second-Order Fault Attack against a Real-World Pairing Implementation](https://eprint.iacr.org/2014/543.pdf) by Johannes Blomer, Ricardo Gomes da Silva, Peter Gunther, Juliane Kramer and Jean-Pierre Seifert

### Nik Unger otr implementation
* [Off-the-Record Messaging](https://crysp.uwaterloo.ca/software/) by Nik Unger.

### General
* [Crypto++ 5.6.5](https://www.cryptopp.com/release565.html)
* [cryptopp](https://github.com/weidai11/cryptopp)
* [The Apache Milagro Cryptographic Library](https://github.com/MIRACL/amcl)
* [DeDiS Advanced Crypto Library for Go](https://github.com/dedis/crypto)
* [Relic](https://github.com/relic-toolkit/relic)
* [Libsodium docs](https://github.com/jedisct1/libsodium-doc)
* [Libsodium: helpers](https://download.libsodium.org/doc/helpers/)
* [TweetNaCl](http://tweetnacl.cr.yp.to/tweetnacl-20140917.pdf) by Daniel J. Bernstein1, Bernard van Gastel, Wesley Janssen, Tanja Lange, Peter Schwabe3 and Sjaak Smetsers
* [NaCl: internals](https://nacl.cr.yp.to/internals.html)
* [HACL: A Verified Modern Cryptographic Library](https://eprint.iacr.org/2017/536.pdf) by Jean Karim Zinzindohoué, Karthikeyan Bhargavan, Jonathan Protzenko and Benjamin Beurdouche
* [Several](https://cryptojedi.org/crypto)
* [Privacy Pass](https://medium.com/@alxdavids/privacy-pass-6f0acf075288) by Alex Davidson
* [Apache Milagro Crypto Library](http://milagro.apache.org/files/amcl-doxygen-1.0.0.pdf)

### Javascript
* [Stanford Javascript Crypto Library](http://bitwiseshiftleft.github.io/sjcl/)

### CIRCL
* [Introducing CIRCL: An Advanced Cryptographic Library](https://blog.cloudflare.com/introducing-circl/) by Kris Kwiatkowski and Armando Faz-Hernández
* [Github repo](https://github.com/cloudflare/circl)

## Quatum computing
* [The Quantum Menace](https://blog.cloudflare.com/the-quantum-menace/) by Armando Faz-Hernández
* [Quantum Computing: Lecture Notes](http://homepages.cwi.nl/~rdewolf/qcnotes.pdf) by Ronald de Wolf
* [Polynomial time algorithms for prime discrete logarithms on a quantum computer](http://www.if.pwr.wroc.pl/~biegansk/PS.pdf) by Peter W. Shor
* [Simulating Physics with Computers](https://people.eecs.berkeley.edu/~christos/classics/Feynman.pdf) by Richard Feynman
* [Quantum Mechanical Computers](http://www.quantum-dynamic.eu/doc/feynman85_qmc_optics_letters.pdf) by Richard Feynman
* [Worst-Case to Average-Case Reductions for Module Lattices](http://perso.ens-lyon.fr/damien.stehle/downloads/MSIS.pdf)
* [Quantum Computing And The New IT Revolution](https://modernciso.com/2019/02/20/quantum-computing-and-the-new-it-revolution/) by Tommaso Gagliardoni

## PostQuantum Crypto
* [PQCHacks: A gentle introduction to post-quantum cryptography](https://media.ccc.de/v/32c3-7210-pqchacks#video&t=908) by djb and Tanja Lange in 32c3.
* [Towards quantum-resistance cryptosystems from supersingular elliptic curve isogenies](http://eprint.iacr.org/2011/506.pdf) by Luca de Feo, David Jao and Jerome Plut.
* [Quantum computers are coming!](https://www.youtube.com/watch?v=c7OHv-L-x50) by Tanja Lange and Daniel J. Bernstein
* [Ring learning with errors](https://en.wikipedia.org/wiki/Ring_learning_with_errors)
* [A low-resource quantum factoring algorithm](https://eprint.iacr.org/2017/352.pdf) by Daniel J. Bernstein, Jean-François Biasse, and Michele Mosca
* [Module-LWE key exchange and encryption:
The three bears](https://www.shiftleft.org/papers/threebears/threebears-draft1.pdf) by Mike Hamburg
* [On Lattices, Learning with Errors, Random Linear Codes, and Cryptography](http://www.cims.nyu.edu/~regev/papers/qcrypto.pdf) by Oded Regev
* [On Agnostic Boosting and Parity Learning](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/2008-On_Agnostic_Boosting-and_Parity_Learning.pdf) by Adam Tauman Kalai, Yishay Mansour and Elad Verbin
* [Post-Quantum Cryptography](https://www.researchgate.net/profile/Nicolas_Sendrier/publication/226115302_Code-Based_Cryptography/links/540d62d50cf2df04e7549388/Code-Based-Cryptography.pdf) by Daniel Bernstein and Johannes Buchmann
* [A Simple Provably Secure Key Exchange Scheme Based on the
Learning with Errors Problem](https://eprint.iacr.org/2012/688.pdf) by Jintai Ding, Xiang Xie and Xiaodong Lin
* [The Learning with Errors Problem](http://www.cims.nyu.edu/~regev/papers/lwesurvey.pdf) by Oded Regev
* [Quantum theory, the Church-Turing principle and the universal
quantum computer](https://web.archive.org/web/20030915061044/http://www.qubit.org/oldsite/resource/deutsch85.pdf) by David Deutsch
* [Post-quantum cryptography –dealing with the fallout of physics success](https://eprint.iacr.org/2017/314.pdf) by Daniel J. Bernstein and Tanja Lange
* [A Post-Quantum Digital Signature Scheme Based on Supersingular Isogenies](https://eprint.iacr.org/2017/186) by Youngho Yoo, Reza Azarderakhsh, Amir Jalali, David Jao and Vladimir Soukharev
* [Quantum Erasure Cryptography](https://arxiv.org/pdf/1512.00808.pdf) by Hatim Salih
* [TESLA: Tightly-Secure Efficient Signatures from Standard Lattices](https://cryptojedi.org/papers/tesla-20160802.pdf) by Erdem Alkim, Nina Bindel, Johannes
Buchmann, Özgür Dagdelen and Peter Schwabe
* [An improved compression technique for signatures based on learning with errors](https://eprint.iacr.org/2013/838.pdf) by Shi Bai and Steven D. Galbraith
* [NTRU Prime](https://ntruprime.cr.yp.to/ntruprime-20160511.pdf) by Daniel J. Bernstein, Chitchanok Chuengsatiansup, Tanja Lange and Christine van Vredendaal
* [An Efficient Quantum Collision Search Algorithm and Implications on Symmetric Cryptography](https://eprint.iacr.org/2017/847.pdf) by André Chailloux, María Naya-Plasencia, and André Schrottenloher
* [Low-communication parallel quantum multi-target preimage search](https://eprint.iacr.org/2017/789.pdf) by Gustavo Banegas and Daniel J. Bernstein

### Hashed-based signatures

* [Hash-Based Signatures presentation](https://www.youtube.com/watch?v=qkqtsnXTMQM&t=1968s) by Andreas Hülsing
* [COSIC seminar "Introduction to Hash Based Signatures"](https://www.youtube.com/watch?v=jiU0ICoiPI0) by John Kelsey

## Searchable symmetric encryption
* [Searchable Symmetric Encryption: Improved Definitions and Efficient Constructions](https://eprint.iacr.org/2006/210.pdf) by Reza Curtmola, Juan Garay, Seny Kamara and Rafail Ostrovsky

## Malware
* [Encrypted Viruses](http://www.cs.virginia.edu/~ww6r/CS4630/lectures/Encrypted_Virus.pdf)
* [Official (ISC)2 Guide to the SSCP CBK, Second Edition](https://books.google.com.ec/books?id=42g1BNUSYPwC&pg=PA98&lpg=PA98&dq=cascade+virus+source+code&source=bl&ots=giqHBUTgnI&sig=HPjGmlzyzbvPpVBad5I0U6drxDI&hl=en&sa=X&ved=0ahUKEwi4yJ-GpOPTAhVr4oMKHeTMA_c4ChDoAQguMAU#v=onepage&q&f=false)
* [The Art of Computer Virus](https://books.google.com.ec/books?id=XE-ddYF6uhYC&pg=PT89&lpg=PT89&dq=cascade+virus+source+code&source=bl&ots=GgNOdq_PJY&sig=Zp9naiUWg7U-MtHunpNQELgGWFI&hl=en&sa=X&ved=0ahUKEwizwr_5o-PTAhUr5oMKHZVSCH4Q6AEITDAH#v=onepage&q=cascade%20virus%20source%20code&f=false)
* [Examples of Malicious Computer Programs](http://www.rbs2.com/cvirus.htm#anchor222250) by Ronald B. Standler
* [Malwaretech](https://www.malwaretech.com/)
* [Common Patterns of Virus Research](http://computervirus.uw.hu/ch02lev1sec1.html)
* [Automatic Transfer Systems (ATS) for Beginners](https://www.malwaretech.com/2016/08/automatic-transfer-systems-ats-for-beginners.html) by MalwareTech

## MPC
* [A Full CryptoCurrency Custody Solution Based on MPC and Threshold ECDSA](https://www.youtube.com/watch?v=Qv4-vh-KJ1s&feature=youtu.be) by Yehuda Lindell

## Passwords
* [SPHINX: A Password Store that Perfectly Hides from ItselfSPHINX: A Password Store that Perfectly Hides from Itself](http://webee.technion.ac.il/~hugo/sphinx.pdf) by Maliheh Shirvanian, Stanislaw Jarecki†, Hugo Krawczyk and Nitesh Saxena

## Cryptocurrencies
* [ZCash Ceremony](http://www.radiolab.org/story/ceremony/)

### Bitcoin
* [Bitcoin and Cryptocurrency Technologies](https://lopp.net/pdf/princeton_bitcoin_book.pdf) by Arvind Narayanan, Joseph Bonneau, Edward Felten, Andrew Miller and Steven Goldfeder

## Usability
* [Obstacles to the Adoption of Secure Communication Tools](http://www.jbonneau.com/doc/ASBDNS17-IEEESP-secure_messaging_obstacles.pdf) by Ruba Abu-Salma, Anastasia Danilova, M. Angela Sasse, Alena Naiakshina, Joseph Bonneau and Matthew Smith
* [Listen to Developers! A Participatory Design Study on Security Warnings for Cryptographic APIs](https://dl.acm.org/doi/abs/10.1145/3313831.3376142) by Peter Leo Gorski, Yasemin  Acar, Luigi  Lo Iacono and Sascha Fahl
* [“We make it a big deal in the company”: Security Mindsets in Organizations that Develop Cryptographic Products](https://www.usenix.org/system/files/conference/soups2018/soups2018-haney-mindsets.pdf) by Julie M. Haney, Mary F. Theofanos, Yasemin Acar and Sandra Spickard Prettyman
* [Developers Deserve Security Warnings, Too: On the Effect of Integrated Security Advice on Cryptographic API Misuse](https://www.usenix.org/system/files/conference/soups2018/soups2018-gorski.pdf) by Peter Leo Gorski, Luigi Lo Iacono, Dominik Wermke, Christian Stransky, Sebastian Möller, Yasemin Acar, and Sascha Fahl
* [Comparing the Usability of Cryptographic APIs](https://www.cl.cam.ac.uk/~rja14/shb17/fahl.pdf) by Yasemin Acar, Michael Backes, Sascha Fahl, Simson Garfinkel, Doowon Kim, Michelle L. Mazurek, and Christian Stransky

## Mailing List
* [Modern Crypto](https://moderncrypto.org/mail-archive/)
* [The Internet Engineering Task Force -IETF-](https://www.ietf.org/mail-archive/web/cfrg/current/maillist.html)
* [Cypherpunks](https://lists.cypherpunks.ca/pipermail)

## Hacking (in general)
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)

## Various
* [Rebooting the Web-of-Trust](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust)
* [Tor Browser Bundle - iSEC Deliverable 1.3](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf)
* [Privacy Enhancement for Internet Electronic Mail: Part I -- Message Encipherment and Authentication Procedures](https://tools.ietf.org/html/rfc1113) by J. Linn
* [Multipurpose Internet Mail Extensions (MIME) Part One: Format of Internet Message Bodies](https://tools.ietf.org/html/rfc2045) by N. Freed and N. Borenstein
* [Exploiting mathematical structures in cryptography](https://pure.tue.nl/ws/files/97946090/20180605_Vredendaal.pdf) by van Vredendaal, C

## Password managers

* [Password Managers: Under the Hood of Secrets Management](https://www.securityevaluators.com/casestudies/password-manager-hacking/)
* [Recovering the Master Password from a Locked Password Manager (1Password 4)](https://blog.securityevaluators.com/recovering-the-master-password-from-a-locked-password-manager-1password-4-5d32cd569907) by Adrian Bednarek