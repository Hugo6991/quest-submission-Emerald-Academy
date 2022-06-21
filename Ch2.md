## Day 1 - Our First Smart Contract | Quests

1. Deploy a contract to account `0x03` called "JacobTucker". Inside that contract, declare a **constant** variable named `is`, and make it have type `String`. Initialize it to "the best" when your contract gets deployed.

3. Check that your variable `is` actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.

![image](https://user-images.githubusercontent.com/48922178/174787105-501bbde3-4d74-4f7a-9500-81894e926749.png)

---

## Day 2 Transactions and Scripts | Queste

1. Explain why we wouldn't call `changeGreeting` in a script.
    
    `changeGreeting` is a function couldn’t return value if users not input anything ?
    
2. What does the `AuthAccount` mean in the `prepare` phase of the transaction?
    
    `AuthAccount` 
    
3. What is the difference between the `prepare` phase and the `execute` phase in the transaction?
    
    
4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.
    
    
- Add two new things inside your contract:
    - A variable named `myNumber` that has type `Int` (set it to 0 when the contract is deployed)
    - A function named `updateMyNumber` that takes in a new number named `newNumber` as a parameter that has type `Int` and updates `myNumber` to be `newNumber`
    
    - var `myNumber:Int`
    - fun`updateMyNumber`
    - `newNumber:Int`
    - int 先隨便輸入預設數字
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c794326d-e517-46d2-9340-50037f0f359d/Untitled.png)
        
    - 再到 Transaction 這邊跑一個新的 function
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bfaadb84-e909-4a59-aa2b-cdeb4e7cccde/Untitled.png)
        
    - newnumber 這個變數因為是 int，所以要先預設輸出數字，右邊才有彈窗
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9da62e52-5458-4ca4-b42f-f804cbc2630f/Untitled.png)
        
    - make a transaction 之後
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/98c8facc-7d37-458a-b013-f4875beb04e1/Untitled.png)
        
    - 輸入數值仍然顯示 12 , why ?
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a50765ee-23d2-4d9d-844a-85bb667068be/Untitled.png)
