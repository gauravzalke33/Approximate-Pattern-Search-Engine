# Approximate-Pattern-Search-Engine
Implementing Hamming Distance, Mismatch based pattern search, neighbourhood generation, and frequent k-mers with mismatches. 

## Included Algorithms

- **Hamming Distance:** Measures mismatches between two DNA strings
- **Approximate Pattern Count:** counts the total number of patterns from the genome allowing missmatches `(<= d)`
- **Approximate Pattern Matching:** finds all the position where pattern appears in the genome with `<= d` missmatches
- **Neighbourhood Generation:** generates all the kmers with d mismatches of a given pattern
- **Frequent Words With Mismatch:** Finds the most frequent approximate kmer in a genome, `combining neighbours + frequency maps`
