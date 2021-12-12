# Building a Blockchain Ledger in Python - Using Streamlit for rapid web app

### **TO RUN:**
navigate to the folder and in the terminal run the Streamlit application by using:
> `streamlit run pychain.py`.

![terminal](https://github.com/t-caseyBCS/Module18-repo/blob/main/images/terminal.PNG)

Once the program runs, it will open a new URL tab on your default web browser

![pychain-genblock](https://github.com/t-caseyBCS/Module18-repo/blob/main/images/pychain-genblock.PNG)

---
### **TO USE:**
- Enter values for the *sender*, *receiver*, and *amount*
    - **sender input:** please enter a name (i.e. John) 
    - **receiver input:** please enter a name (i.e. Sally) 
    - **amount input:** please enter a float or int (i.e. 50.00 or 50) 
- You can also change the *Block Difficulty* which determines the hash difficulty for the miner in the form of number of zeros '0's needed at the beginning of the hash to add a new block
- then click the `Add Block` button. 

- Do this several times to store several blocks in the ledger.

### Notice how the Ledger updates to indicate the block has been added

![pychain-block1](https://github.com/t-caseyBCS/Module18-repo/blob/main/images/pychain-block1.PNG)

### Play with the `Block Difficulty` and watch the Ledger grow
![pychain-block2](https://github.com/t-caseyBCS/Module18-repo/blob/main/images/pychain-block2.PNG)

---
### **HOW TO VERIFY**
Verify the block contents and hashes 2 ways
1. Validate the chain by clicking the `Validate Chain` button
2. Use the `Block Inspector` drop-down menu to see specific block records

    ![pychain-verify](https://github.com/t-caseyBCS/Module18-repo/blob/main/images/pychain-verify.PNG)
