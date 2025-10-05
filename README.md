# WebSocket-using-Real-Time-Chat-Application-

### 1.Goto Aws Console Create DynamoDB Table.
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/aa4b1c22ea9dbf49e609f3e928f09246f600ff2f/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2017_56_07.png)
### 2.Create Table 
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20table%20_%20Amazon%20DynamoDB%20Management%20Console%20_%20DynamoDB%20_%20us-east-1%20-%20Google%20Chrome%2004-10-2025%2017_57_59.png)

### 3.Goto AwsConsole LAMBDA create three lambda functions 
  ### 1. create lambda function for Connection.
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/API%20Gateway%20-%20Create%20WebSocket%20API_%20Step%201%20-%20Google%20Chrome%2004-10-2025%2016_52_15.png)
### 2.Create Function.
### 3. In This Code Section Write The Following Code.
4. ![tmageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/API%20Gateway%20-%20Create%20WebSocket%20API_%20Step%201%20-%20Google%20Chrome%2004-10-2025%2016_54_05.png)
### 5. Deploy The Code.
### 6. Go To The Configuration Tab In The Navigation Bar click Environment variable WEBSOCKET_TABLE in the key Your Table Name.
### 7. Go To The Permission tab cilck IAM URL Add permission put item in DynamoDb table. 
### Same As Create Other Two Lambda Functions Disconnect SendMessage.

### 2. Create Api Gateway.

### 1.Goto Aws Console Create Api Gateway.
### 2.Choose Websocket Api click Bulid Option.
### 3.Configure Api.
 ![iamgeAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/API%20Gateway%20-%20Create%20WebSocket%20API_%20Step%201%20-%20Google%20Chrome%2004-10-2025%2016_39_33.png)
 ### Add Routes
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2016_59_21.png)
### Add Integeration
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2016_59_49.png)
## Add Stage 
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2016_59_58.png)
## Create 
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2017_00_09.png)

### 4. Click Create APi.
### Go To Stage Copy the Websocket Url Paste Postman Or Whatever You Use.
![imageAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Create%20function%20_%20Functions%20_%20Lambda%20-%20Google%20Chrome%2004-10-2025%2017_02_35.png)
### paste Url 
![imageALt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Online%20Websockets%20Tester%20-%20Debug%20Client%20Tool%20-%20Google%20Chrome%2004-10-2025%2018_30_49.png)
### It Will Store On DynamoDb Table 
![iamgeAlt](https://github.com/yogeshAce6/WebSocket-using-Real-Time-Chat-Application-/blob/edf2454ce6d63fd38899cc9c141610b472994dce/WebSockets/Online%20Websockets%20Tester%20-%20Debug%20Client%20Tool%20-%20Google%20Chrome%2004-10-2025%2018_31_19.png)


