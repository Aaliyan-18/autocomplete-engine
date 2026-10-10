#  Trie-Based Autocomplete Engine

A robust and efficient "Autocomplete Engine" built using the "Trie (Prefix Tree)" data structure[cite: 1.8]. This project was developed as part of our Data Structures and Algorithms (DSA) coursework[cite: 1.8] to demonstrate optimized string searching, real-time prefix matching, and scalable memory management.

---

##  Features

- **Fast Insertion (`O(L)`)**: Efficiently inserts words into the Trie structure, where each node represents a character[cite: 1.8].
- **Prefix Search (`O(L)`)**: Instantly checks whether a given prefix exists in the dictionary[cite: 1.8].
- **Real-Time Autocompletion (`O(L + N)`)**: Utilizes Depth-First Search (DFS) traversal from the prefix node to retrieve all valid subsequent word completions[cite: 1.8].
- **Optimized Performance**: Significantly faster than traditional linear search methods for large text datasets[cite: 1.8].

---

##  Complexity Analysis

| Operation | Time Complexity | Description |
| :--- | :--- | :--- |
| **Insert Word** | $O(L)$ | $L$ is the length of the word being inserted[cite: 1.8]. |
| **Search Prefix** | $O(L)$ | $L$ is the length of the prefix[cite: 1.8]. |
| **Autocomplete** | $O(L + N)$ | $L$ is the prefix length and $N$ is the total number of suggestions returned[cite: 1.8]. |
| **Space Complexity** | $O(N \times L)$ | Storage required for nodes representing the words[cite: 1.8]. |

---

## 🛠️ Data Structures & Algorithms Used
- **Trie (Prefix Tree)**: A specialized tree structure designed specifically for handling strings and enabling rapid prefix-based lookups[cite: 1.8].
- **DFS (Depth-First Search)**: Used recursively to traverse sub-trees and extract all possible word endings from a matched prefix node[cite: 1.8].

---

##  Real-World Applications
- Search engine query boxes (e.g., Google search suggestions)[cite: 1.8]
- IDE code completion and IntelliSense[cite: 1.8]
- Mobile phone keyboard text predictors[cite: 1.8]
- E-commerce search bars[cite: 1.8]

---

## 👥 Group Members
- **M. Aaliyan Ahmed** (FA24-BSE-123)[cite: 1.8]
- **Sayed Abdullah Jawwad** (FA34-BSE-083)[cite: 1.8]
---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
