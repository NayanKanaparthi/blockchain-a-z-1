# Understanding SHA256 Hash

* Developed by the NSA
* 64 Characters long
* Hexadecimal hash, 0-9, A-F
* Works for ANY kind of file


The 5 requirements for Hash Algorithms:
1. One-Way. Cannot go from the hash to the data. No way to restore or reverse engineer.
2. Deterministic. The same data should have the same hash always.
3. Fast Computation
4. The Avalanche Effect. The smallest change in data should completely change the hash.
5. Must withstand collisions.

 **Reading**: *On the Secure hash Algorithm family* by Wouter Penard & Tim van Werkhoven
