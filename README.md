# -lib-ECDSA
This is a project libECDSA for PHP code. In cryptography, the Elliptic Curve Digital Signature Algorithm (ECDSA) offers a variant of the Digital Signature Algorithm (DSA) which uses elliptic curve cryptography(wikipedia). 

# Use
$curve       = NIST::getCurve('#NISTbitLenght');
$private_key = KeyPair::import(#YourPrivateKey);
$signature   = new Signature($curve, $private_key, $hashM);
