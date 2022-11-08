
<p style="font-size:14px" align="right">
<a href="https://m.do.co/c/2cea00d4f9bble" target="_blank">Deploy your VPS using our referral link to get 100$ free bonus for 60 days <img src="https://user-images.githubusercontent.com/50621007/183284313-adf81164-6db4-4284-9ea0-bcb841936350.png" width="30"/></a>/
</p>

<p align="center">
  <img height="50" height="auto" src="https://user-images.githubusercontent.com/38981255/184088981-3f7376ae-7039-4915-98f5-16c3637ccea3.PNG">
</p>

# Tutorial Become a Master Node Inery Blockchain Task 2

Dokumen Innery Official :
> [Node Lite & Master](https://docs.inery.io/docs/category/lite--master-nodes)

Explorer Inery BlockChain :
> [Explorer Inery BlockChain](https://explorer.inery.io/ "Explorer Inary")

# Inery Task 2 Update
Because Task 1 has been approved, let's move on to the next step, task 2

**First of all, check if your account has been approved?**
NOTE: If you have problems logging in, use the incognito tab in your browser

<p align="center">
  <img height="auto" height="auto" src="https://user-images.githubusercontent.com/112532410/200574316-225c2964-90ba-4f90-8bba-5d4f20d657c6.jpg">
</p>

- OKAY, Time to go to task 2
# Open your wallet
```
cline wallet unlock --name Your_Wallet_Name --password Your_Wallet_Password
```
- Created ABI & WASM
```
cline get code inery.token -c token.wasm -a token.abi --wasm
``` 
- Set account code
```
cline set code -j Your_Wallet_Name token.wasm
cline set abi Your_Wallet_Name token.abi
```

- Create New Token
```
cline push action inery.token create '["Your_Account_Name", "Supply CurrencyCode"], "token description/memo"' -p Your_Account_Name
```
**Example**
👇👇👇👇👇
```
cline push action inery.token create '["mr.pendol", "10000.0000 MRPDL"], "Free Coffee"' -p mr.pendol
```

- Issue New Token
```
cline push action inery.token issue '["YourAccountName", "Supply CurrencyCode", "detail"]' -p YourAccountName
```
**Example**
👇👇👇👇👇
```
cline push action inery.token issue '["mr.pendol", "10000.0000 CPI", "Free Coffee"]' -p mr.pendol
```
- Send Token, Minimum 10 transactions to 10 people
```
cline push action inery.token transfer '["Your_Account_Name", "Token_Receiver", "1.0000 Your_Token_Name", "My Hot Coffee For You"]' -p Your_Account_Name
```
**Example**
👇👇👇👇👇
```
cline push action inery.token transfer '["Your_Account_Name", "inery", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "mr.pendol", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", ".kodomo", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "bigpool", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", ".asfi", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "1atau2", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "1phdchan", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "abc1", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "abdulyunti", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "abuyaskur", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "adacansu", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
cline push action inery.token transfer '["Your_Account_Name", "agungun", "1.0000 MRPDL", "My Hot Coffee For You"]' -p Your_Account_Name
```
## ✅ Done

**Go to Your Inery Account Click Task 2 Click Finish and wait for it to be APPROVED**
