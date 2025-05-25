# Mermin–Peres Magic Square Game (MPMS Game)

The **Mermin–Peres Magic Square (MPMS) Game** is a puzzle that comes from quantum physics. It's played by two players—**Alice** and **Bob**—who must work together without interacting with each other during the game.

The game is based on a $3×3$ grid, where each cell contains either $0$ or $1$. The rules are:

- Alice gets a random **row number** (from $0$ to $2$) and must give the three values in that row.
- Bob gets a random **column number** (from $0$ to $2$) and must give the three values in that column.
- To win a round:
  - The sum of Alice’s row values must be even.
  - The sum of Bob’s column values must be odd.
  - Their answers must **agree** on the shared cell (where the row and column meet).

At first, the rules may seem easy to follow—but it turns out that it’s **impossible** to always win this game using only classical (non-quantum) strategies.

---

### Classical vs Quantum Strategies

In this project, we explore how both **classical** and **quantum** strategies can be used to play the MPMS game. While classical strategies can win **at most 8 out of 9 times** (around **88.9% success rate**), the quantum strategy implemented by us wins **every single time**—achieving a **perfect 100% accuracy**.

This remarkable advantage is made possible by quantum features like **entanglement** and **contextuality**, which give Alice and Bob a stronger-than-classical correlation without any communication. 

Detailed explanations and implementations of both strategies will follow in the next sections.
