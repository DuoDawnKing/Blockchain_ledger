# Blockchain_ledger

The blockchain ledger is a small project that is focused on saving data from a sender and reciever including the amount that was sent. This is important for financial transactions records that the blocks of the ledger will store. In order to do this we will first create a few dataclasses which will be called block, Record, Pychain. Record will be used to save the input user data, which will be used when making the block. The block data class is used create a block that will have creator id, timestamp and will pull over the previous hash block to ensure that each block data is accurate and not manipulated. Pychain is used to chain blocks and will report if a blockchain is valid or invalid based off of POW. The code is set up to work on streamlit, which will have a a set up that shows sender, reciever, and amount, plus a side bar which will show each block that has been created and saved into the ledger, which if click on will display the information on the block. Attached to the file is an image that displays the code working and multiple results to verify the work. In the code, i have confirmation checkbox and more for sending and recieving information to ensure that the user would be able to verify that this is the intended sender and reciever to ensure that they are aware of the accuracy of the input data.
