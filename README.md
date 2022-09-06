![alt text](https://static.seekingalpha.com/uploads/2019/12/18/48200183-15766884216563983_origin.jpg)


# Bitcoin Miner

## Project Description
Build a bitcoin miner using Erlang and Actor Model which works on multi-core machines and do the job of generating a random string with an initial string as your gator ID & find the hash of that string using SHA-256 with k leading 0's provided by the user and mined coins with the highest leading zeros. 


## Project Requirements
### Input
The input provided (as command line to yourproject1.fsx) will be, the required number of 0’s of the bitcoin.1


### Output
Print, on independent entry lines, the input string, and the correspondingSHA256 hash separated by a TAB, for each of the bitcoins you find. Obviously, your SHA256 hash must have the required number of leading 0s (k= 3 means3 0’s in the hash notation).  An extra requirement, to ensure every group finds different coins, is to have the input string prefixed by the gator link ID of one of the team members.

### Example
1
adobra;kjsdfk11 0d402337f95d018438aad6c7dd75ad6e9239d6060444a7a6b26299b261aa9a8b

indicates that the coin with 1 leading 0 is adobra;kjsdfk11and it is prefixed by the gatorlink ID adobra.

## Authors

| Name | GitHub ID | UF ID |
|------|-----------|-------|
|Shreya Kasturia|shreyakasturia | 5095-8404 |
|Adityansh Kapasia|Adityanshkapasia| 9707-8368 |

## Built On

- Programming language: Erlang
- Operating System: Mac OS
- Programming Tool: Visual Studio Code
