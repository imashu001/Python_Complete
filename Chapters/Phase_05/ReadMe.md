Phase 5: Python Collections Deep Dive
Strings
Methods
Slicing
Formatting
f-strings
Encoding
Lists
Methods
Copying
Nested lists
Tuples
Sets
Dictionaries
Methods
Dictionary views
Hashing


Module 1: Strings & Text ProcessingFocus on how Python handles text, formatting, and underlying byte representations.

Strings & Methods: Basic operations, upper/lower, strip, replace, split, join.Slicing: Indexing, positive/negative indices, step values ([start:stop:step]).

Formatting & f-strings: Old-style formatting (.format()), modern f-strings, alignment, and number formatting.

Encoding & Decoding: Introduction to Unicode, UTF-8, ASCII, .encode(), and .decode() (great for transitioning into data handling).

Module 2: Ordered Mutable/Immutable Collections (Lists & Tuples)

Focus on sequences that maintain order, how they are stored in memory, and manipulation.

Lists & Methods: Creation, appending, inserting, sorting, popping, removing.
Copying: Shallow copies vs. deep copies (copy() module, slicing tricks), mutability implications.
Nested Lists: Matrices, multi-dimensional data access.Tuples: When and why to use immutable sequences, tuple unpacking, immutability benefits.

# Module 3: Unordered Collections & Advanced Concepts (Sets & Dictionaries)
## Focus on key-value mapping, uniqueness, and the performance benefits of hashing.

Sets: Mathematical set operations (union, intersection, difference), removing duplicates.
Dictionaries & Methods: Key-value pairs, accessing, updating, .get(), .pop(), .keys(), .values().
Dictionary Views: Dynamic views on keys and values, iteration patterns.
Hashing & Mutability: What makes an object hashable, why lists can't be dictionary keys, and the underlying performance ($O(1)$ lookup).