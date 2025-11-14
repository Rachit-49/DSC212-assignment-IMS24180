# DSC212-assignment-IMS24180  
## Modularity on the Karate Club Graph

**Student Name:** Rachit Srivastava   
**Roll Number:** IMS24180    
**Course:** DSC212 — Graph Theory Assignment     


---

### **Project Overview**
This repository contains my submission for **DSC212 – Research Assignment** on  
**“Modularity on the Karate Club Graph.”**

The goal is to implement **spectral modularity-based community detection** on  
Zachary’s Karate Club social network using **NetworkX**, **NumPy**, and **Matplotlib**.

The method recursively applies the **leading eigenvector** of the **modularity matrix**  
to partition the graph until no further modularity gain is possible (λ₁ ≤ 0).


### **Outputs**
-Colored community plots after each recursive split

-Final community structure (4 communities)

-Modularity value Q of the final partition

-Centrality metric plots for top nodes

### **Key Concepts**

**Modularity (Q)**: Measures how well a network divides into communities compared to a random model.

**Spectral Modularity**: Uses eigen-decomposition of the modularity matrix to find optimal splits.

**Recursive Bisection**: Re-applies splitting until no positive eigenvalue remains.

**Centrality Metrics**: Used to identify hubs, bridges, and cluster cores.

### **Result Summary**
The algorithm identified ≈ 4 modularity-stable communities.

Each group corresponds to densely connected subgroups within the original two factions.

Bridge nodes (high betweenness) link these subgroups, matching real-world social roles.

---
