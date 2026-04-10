# Information Extraction (NLP, INFO 159 @ UC Berkeley)

This project extracts relationships from text using pattern-based methods.

## Task

Given sentences about animals, extract relationships like:
- kangaroo → marsupial  
- giraffe → mammal  

## Approach

- Used pattern matching (e.g. "such as", "is a") to identify relationships  
- Extracted candidate pairs based on sentence structure  
- Aggregated results to build a simple taxonomy  

## Limitations

- Pattern matching is precise but misses many valid sentences  
- Struggles with indirect or multi-sentence relationships  
