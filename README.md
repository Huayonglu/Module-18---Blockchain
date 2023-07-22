# Module-18---Blockchain Assignment

![alt=""](Images/application-image.png)

## Brief Introduction

I have developed a blockchain program to help the customer store ledgers for transactions. Each transaction includes the three atrributes which are sender, receiver and transferred amount. The information is stored in the individual blocks, whcih composite a blockchain. The procedure of compiling the programme is the following

1. Create a Record class first whcih will be used as a data type for the input data of the successive new block. This Record class includes three attributes as mentioned above. 

2. Create a new block with block_hash() function built under it to fetch the hash code. This new block is used to store each record.

3. Create a new blockchain called PyChain, which also defines the proof_of_work function to fetch the right block hash, add_block function and blockchain verification function (is_value).

4. All above work is called back end programming. Then we will estbalish the front end using streamlit. The front end interface is to estbalish three text input cells to store the informaiton for each transaction. 

5. Within the streamlit programme, it carries out storing the informaiton to a new block, add block to the chain and conver the chain information to dataframe for neat express on the screen.

6. It also presents a button for the block chain verification. The hash code difficulty is also adjustable by using st.sideslider inputs. A block inspectors also is prsented to help user to check each transaction. 

## Test Result

### Add Blocks

![alt=""](Assignment_photos/Test%20-%201-%20Add%20Blocks.PNG)

### Change Difficulty

![alt=""](Assignment_photos/Test%20-%202%20-%20Change%20Difficulty.PNG)

### Check Block Inspector

![alt=""](Assignment_photos/Test%20-%203%20-%20Check%20Block%20Inspector.PNG)

### Validate Chain

![alt=""](Assignment_photos/Test%20-%204%20-%20Validate%20Chain.PNG)

## Conclusion

The programming has been completed and tested to the requirements. The compiler is happy with the result. Thanks! 




