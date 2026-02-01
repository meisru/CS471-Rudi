# TCP Analysis - Wireshark Capture 

## Part 2, Task 2: TCP Three-Way Handshake

**Step 2: Sequence and Acknowledgment Numbers:**

The TCP three-way handshake:

![TCP Handshake](Screenshots/Screenshot1.png)

Full Connection:

![Connection](Screenshots/Screenshot2.png)

---

**Step 3: Observed data packets**

![Data Transfer](Screenshots/Screenshot3.png)

---

**Step 4: Connection Termination**

![TCP Termination](Screenshots/Screenshot4.png)

The connection closes using:
1. **FIN-ACK**: Client initiates close
2. **ACK**: Server acknowledges
3. **FIN-ACK**: Server also closes
4. **ACK**: Client acknowledges