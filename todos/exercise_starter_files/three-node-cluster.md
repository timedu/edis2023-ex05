
# Three-Node Cluster with rqlite

In the Sections 1-15, present the necessary commands and their response

### Start the cluster

---

## A. Is data replicated in the nodes?

### 1. Store some data in the first node (rqlite_1)

### 2. Check if the data can be found in the other nodes (rqlite_2, rqlite_3)

### Give the answer to the question A

---

## B. Can you write to more than one node?

### 3. Store data in a node other than the first node

### 4. Check also if the data can be found in the other nodes

### Give the answer to the question B

---

## C. Can you write if one replica is out of the game?

### 5. Stop one of the nodes (rqlite_2 or rqlite_3)

### 6. Try to store data in the first node (rqlite_1)

### Give the answer to the question C

---

## D. What happens when the replica comes back into the game?

### 7. Restart the node you stopped

### 8. Check what data is in that node

### Give the answer to the question D

---

## E. Which of the three running replicas is the leader?

### 9. Check which of the nodes is the leader node 

### Give the answer to the question E

---

## F. What if two replicas are down, can you write?

### 10. Stop two of the nodes (rqlite_2 and rqlite_3)

### 11. Try to store data in the first node (rqlite_1)

### Give the answer to the question F

---

## G. When the leader node crashes, which node becomes leader or does no one become leader?

### 12. Restart the nodes you stopped (rqlite_2 and rqlite_3) and stop the first node (rqlite_1)

### 13. Check which of the nodes is the leader node  

### Give the answer to the question G

---

## H. What happens when the previous leader gets up, is it the leader again?

### 14. Restart the first node (rqlite_1)

### 15. Check which of the nodes is the leader node

### Give the answer to the question H

---
