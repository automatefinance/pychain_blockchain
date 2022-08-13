# pychain_blockchain
Pychain powered blockchain application with a streamlit UI.

## Technologies 
streamlit, pandas, hashlib, streamlit, float8(pickeltools), datetime 

## Installation guide
commands for install...
pip install streamlit, pip install pandas, pip install hashlib, pip install datetime

## Usage 
go to /picVideoDemo for full visuals...
User Interface Instructions:

SIDEBAR:
Block Difficulty Slider (1:5): 
1 being the easiest, 5 being the highest the slider selects the dificulty of the hash function. Whatever it is set to when the 'Add Block' button is pressed will be the difficulty. Higher the difficulty the slower the transaction, but the hardest to hack or reverse engineer in terms of computing power.
![60C9DD47-E9C0-447E-9C6E-17C26F0593E8_4_5005_c](https://user-images.githubusercontent.com/98767273/184467621-0f65e7e0-73d2-48de-bffd-916dc34ba27b.jpeg)

Block Inspector Drop Down:
Drop down menu where you can view the details of any block(transaction) that has occured on the blockchain.
![A2D9CAFE-2B87-429C-8724-DF5EDCA47207](https://user-images.githubusercontent.com/98767273/184467822-2f454aeb-e69b-4609-b02e-0e95e5cc3a38.jpeg)

MAINPAGE:
User Input Text Box(s):
Where the sender inputs their information, the receivers information, and how much they want to send to the receiver.
![34A7F8A7-8CCB-4689-A461-67561C1ED873](https://user-images.githubusercontent.com/98767273/184467927-0036b908-ce8a-4716-9f8c-4953ddbe77d8.jpeg)

The PyChain Ledger:
Where all the transactions are stored and asigned a hash function that is related to the data of the parent block, the block itself, and the block that comes after it. Therefore, if anything/anyone maliciously changed the data, the data of every block will change. The 'Validate Chain' button verifies the block based on the hash function.
![7278E3B0-D3B3-4346-BB04-6AD8ACE54B57](https://user-images.githubusercontent.com/98767273/184468059-a879383e-0a16-47fc-beee-7f8f716aad87.jpeg)

## Contributors 
Ethan Rosenberg (Automate Finance)

## License 
None 

