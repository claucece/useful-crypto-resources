# Useful Crypto-related Resources

## OTR

###OTRv2

* [Finite-State Security Analysis of OTR Version 2](http://www.jbonneau.com/doc/BM06-OTR_v2_analysis.pdf) by Joseph Bonneau and Andrew Morrison. 
* [Protocol](https://otr.cypherpunks.ca/Protocol-2.0.2.txt) by Nikita Borisov and Ian Goldberg.
* [Secure Off-the-Record Messaging](https://www.dmi.unict.it/diraimondo/web/wp-content/uploads/papers/otr.pdf) by Mario Di Raimondo, Rosario Gennaro and Hugo Krawczyk 

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

### Blockcipher

#### In general
* [Evaluation of Some Blockcipher Modes of Operation](http://web.cs.ucdavis.edu/~rogaway/papers/modes.pdf) by Phillip Rogaway.

## Symmetric key algorithm

### DES
* [On the Security of Multiple Encryption](http://cs.jhu.edu/~sdoshi/crypto/papers/p465-merkle.pdf) by Ralph C. Merkle and Martin E. Hellman.

## Key Exchange 

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
* [How to design an elliptic-curve signature system](https://blog.cr.yp.to/20140323-ecdsa.html)by blog.cr.yp.to
 
#### In general
* [Elliptic Curves for Security draft-irtf-cfrg-curves-02](https://tools.ietf.org/html/draft-irtf-cfrg-curves-02#section-6.2): an algorithm for deterministically generating parameters for elliptic curves over prime fields by A. Langley.
* [A brief discussion on selecting new elliptic curves](http://csrc.nist.gov/groups/ST/ecc-workshop-2015/papers/session4-costello-craig.pdf) by Craig Costello, Patrick Longa, and Michael Naehrig 

### Edwards Curve

#### Theory

#### Encoding
* [Deterministic Encoding into Twisted Edwards Curves](https://www.researchgate.net/publication/304621009_Deterministic_Encoding_into_Twisted_Edwards_Curves) by Wei Yu, Kunpeng Wang, Bao Li and Song Tian. 

#### ed448

* [Ed448-Goldilocks](http://ed448goldilocks.sourceforge.net/) by sourceforge. 
* [Mike Hamburg Implementation](https://sourceforge.net/p/ed448goldilocks/code/ci/decaf/tree/).
* [STRIKE implementation](https://github.com/twstrike/ed448).  
* [Ed448-Goldilocks, a new elliptic curve](https://eprint.iacr.org/2015/625.pdf) by Mike Hamburg. 

#### ed225519
* [Implementation](https://ed25519.cr.yp.to/python/ed25519.py) by Daniel J. Bernstein. 

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

###Schnorr signatures
* [Schnorr Signatures: An Overview](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust/blob/master/topics-and-advance-readings/Schnorr-Signatures--An-Overview.md) by Christopher Allen.

###EdDSA
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-05): The elliptic curve signature scheme Edwards-curve Digital Signature Algorithm (EdDSA) is described by S. Josefsson. 
* [Ed25519 and Ed448 for DNSSEC](https://tools.ietf.org/id/draft-sury-dnskey-ed25519-02.xml) by O. Sury

### XEdDSA
* [The XEdDSA and VXEdDSA Signature Schemes](https://whispersystems.org/docs/specifications/xeddsa/#curve448) by Trevor Perrin. 

## Models

### The Random Oracle Model
* [The random oracle model: a twenty-year retrospective](https://eprint.iacr.org/2015/140.pdf) by Neal Koblitz and Alfred J. Menezes. 

## Protocol

### Sociallist Millionaire Protocol (SMP)
* [Socialist Millionaire Protocol Passphrase Generator](https://github.com/dillbyrne/smpp-generator) by dillbyrne. 

### Double Ratchet
* [The Double Ratchet Algorithm](https://whispersystems.org/docs/specifications/doubleratchet/) by Trevor Perrin (editor) and Moxie Marlinspike.

## Schemes

* [Folklore, Practice and Theory of Robust Combiners](http://eprint.iacr.org/2002/135.pdf) by Amir Herzberg. 

## Security

* [Chosen-Ciphertext Security of Multiple Encryption](https://www.cs.nyu.edu/~dodis/ps/2enc.pdf) by Yevgeniy Dodis and Jonathan Katz. 
	
## Maths

## Modular Arithmetic
* [Barret Reduction](https://en.wikipedia.org/wiki/Barrett_reduction) in Wikipedia. 

## Compendia 
* [Theory of Cryptography: 9th Theory of Cryptography Conference, TCC 2012](https://books.google.com.ec/books?id=iWirCAAAQBAJ&pg=PA223&lpg=PA223&dq=malleable+symmetric+schemes&source=bl&ots=3oszTtlOhU&sig=evzVsQk3DbLMdkZLVY_O6RD5BfQ&hl=en&sa=X&ved=0ahUKEwjrh4XU2rPPAhUFox4KHY-UAS0Q6AEIKjAD#v=onepage&q=malleable%20symmetric%20schemes&f=false), edited by Ronald Cramer.
* [Recommendation for Key Management](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) by Elaine Barker in NIST. 
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/groups/ST/toolkit/documents/SP800-56Arev1_3-8-07.pdf) by Elaine Barker, Don Johnson, and Miles Smid in NIST. 

## Library

### Pairing-based cryptography
* [The PBC (Pairing-Based Cryptography) library](https://crypto.stanford.edu/pbc/) by Ben Lynn.

### Nik Unger otr implementation
* [Off-the-Record Messaging](https://crysp.uwaterloo.ca/software/) by Ian Goldberg. 


## PostQuantum Crypto
* [PQCHacks: A gentle introduction to post-quantum cryptography](https://media.ccc.de/v/32c3-7210-pqchacks#video&t=908) by djb and Tanja Lange in 32c3.
* [Towards quantum-resistance cryptosystems from supersingular elliptic curve isogenies](http://eprint.iacr.org/2011/506.pdf) by Luca de Feo, David Jao and Jerome Plut. 

## Mailing List
* [Modern Crypto](https://moderncrypto.org/mail-archive/)
* [The Internet Engineering Task Force -IETF-](https://www.ietf.org/mail-archive/web/cfrg/current/maillist.html)
* [Cypherpunks](https://lists.cypherpunks.ca/pipermail)

## Hacking (in general)
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)

## Various
* [Rebooting the Web-of-Trust](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust)
* [Tor Browser Bundle - iSEC Deliverable 1.3](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf)

----------------------------------------------------------------------------
# Programming

## Golang

### General
* [The Go Blog](https://blog.golang.org/)
* [Open My Mind](http://openmymind.net/) by Karl Seguin.
* [Go Playground](https://play.golang.org/)
* [Useful resources](https://github.com/golang/go/wiki#getting-started-with-go)

### Books
* [An Introduction to Go Programming](https://www.golang-book.com/books/intro) 

### Strings
* [Access to the unicode and convert to string](http://stackoverflow.com/questions/19231506/go-golang-access-string-as-character-value)
* [Count](https://golang.org/src/strings/strings.go?s=1960:1989#L67)

### Convert
* [Rune to Int](http://stackoverflow.com/questions/21322173/convert-rune-to-int)
* [strconv](https://golang.org/pkg/strconv/)

### Arrays and slices
* [Controlling Array Growth in Golang](http://openmymind.net/Controlling-Array-Growth-In-Golang/) by Karl Seguin
* [Arrays, Slices and Maps](https://www.golang-book.com/books/intro/6)
* [Arrays, slices (and strings): The mechanics of 'append'](https://blog.golang.org/slices)
* [Go Slices: usage and internals](https://blog.golang.org/go-slices-usage-and-internals)
* [SliceTricks](https://github.com/golang/go/wiki/SliceTricks)

### ForLoop
* [Control structures - Go for loop, break, continue, range](http://golangtutorials.blogspot.com/2011/06/control-structures-go-for-loop-break.html)

### Go Check
* [GoCheck](https://github.com/go-check/check)

----------------------------------------------------------------------------
# Useful
* [ADR tools](https://github.com/npryce/adr-tools)


----------------------------------------------------------------------------
# Code for Tor Browser High Security Mode
In high security mode, Tor only allows PNG images to be available.

If your website must support non-PNG images like SVG, you can set up a fallback image
like so [(Ref.)](https://css-tricks.com/a-complete-guide-to-svg-fallbacks/):

1. With HTML:
```
<object data="your.svg" type="image/svg+xml"> <img src="yourfallback.jpg" /> </object>
```
2. With CSS, which naturally throws away rules that the browser doesn't understand:
```
.image-with-fallback {
    background-image: url(fallback.png);
        background-image: url(your.svg), none;
}{}
```
[Why is SVG a problem? Pg 16 in this iSEC report](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf).
