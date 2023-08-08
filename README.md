
# Cheatsheet for Opcodes

A brief description of all the existing opcodes and their functionalities




## Instructions



| Opcode | Name     | Description                |
| :-------- | :------- | :------------------------- |
| `00` | `STOP` | Halts Execution |
| `01` | `ADD` | Addition Operation |
| `02` | `MUL` | Multiplication Operation |
| `03` | `SUB` | Subtraction Operation |
| `04` | `DIV` | Integer Division Operation |
| `05` | `SDIV` | Signed Integer Division Operation |
| `06` | `MOD` | Modulo Remainder Operation |
| `07` | `SMOD` | Signed Modulo Remainder Operation |
| `08` | `ADDMOD` | Modulo Addition Operation |
| `09` | `MULMOD` | Modulo Multiplication Operation |
| `0A` | `EXP` | Expotential Operation |
| `0B` | `SIGNEXTEND` | Extended Length of Two's Complement Signed Integer |
| `10` | `LT` | Less-Than Comparison |
| `11` | `GT` | Greater-Than Comparison |
| `12` | `SLT` | Signed Less-Than Comparison |
| `13` | `SGT` | Signed Greater-Than Comparison |
| `14` | `EQ` | Equality Comparison |
| `15` | `ISZERO` | Simple Not Operator |
| `16` | `AND` | Bitwise AND Operation |
| `17` | `OR` | Bitwise OR Operation |
| `18` | `XOR` | Bitwise XOR Operation |
| `19` | `NOT` | Bitwise NOT Operation |
| `1A` | `BYTE` | Retrieve Single Byte From Word |
| `1B` | `SHL` | Left Shift Operation |
| `1C` | `SHR` | Logical Right Shift Operation |
| `1D` | `SAR` | Arithmetic Right Shift Operation |
| `20` | `SHA3` | Compute Keccak-256 Hash |
| `30` | `ADDRESS` | Get Address of Currently Executing Account |
| `31` | `BALANCE` | Get Balance of the Given Account |
| `32` | `ORIGIN` | Get Caller Address |
| `34` | `CALLVALUE` | Get Deposited Value by the Instruction/Transaction Responsible for this Execution |
| `35` | `CALLDATALOAD` | Get input data of current environment|
| `36` | `CALLDATASIZE` | Get size of input data in current environment |
| `37` | `CALLDATACOPY` | Copy input data in current environment to memory |
| `38` | `CODESIZE` | Get size of code running in current environment |
| `39` | `CODECOPY` | Copy code running in current environment to memory |
| `3A` | `GASPRICE` | Get price of gas in current environment |
| `3B` | `EXTCODESIZE` | Get size of an account’s code |
| `3C` | `EXTCODECOPY` | Copy an account’s code to memory |
| `3D` | `RETURNDATASIZE` | Get size of output data from the previous call from the current environment |
| `3E` | `RETURNDATACOPY` | Copy output data from the previous call to memory |
| `3F` | `EXTCODEHASH` | Get hash of an account’s code |
| `40` | `BLOCKHASH` | Get the hash of one of the 256 most recent complete blocks |
| `41` | `COINBASE` | Get the block’s beneficiary address |
| `42` | `TIMESTAMP` | Get the block’s timestamp |
| `43` | `NUMBER` | Get the block’s number |
| `44` | `PREVRANDO` | Get the previous block’s RANDAO mix |
| `45` | `GASLIMIT` | Get the block’s gas limit |
| `46` | `CHAINID` | Get the chain ID |
| `47` | `SELFBALANCE` | Get balance of currently executing account |
| `48` | `BASEFEE` | Get the base fee |
| `50` | `POP` | Remove item from stack |
| `51` | `MLOAD` | Load word from memory |
| `52` | `MSTORE` | Save word to memory |
| `53` | `MSTORES` | Save byte to memory |
| `54` | `SLOAD` | Load word from storage |
| `55` | `SSTORE` | Save word to storage |
| `56` | `JUMP` | Alter the program counter |
| `57` | `JUMPI` | Conditionally alter the program counter |
| `58` | `PC` | Get the value of the program counter prior to the increment corresponding to this instruction |
| `59` | `MSIZE` | Get the size of active memory in bytes |
| `5A` | `GAS` | Get the amount of available gas, including the corresponding reduction for the cost of this instruction |
| `5B` | `JUMPDEST` | Mark a valid destination for jumps |
| `5F` | `PUSH0` | Place 0 byte item on stack |
| `60` | `PUSH1` | Place 1 byte item on stack |
| `61` | `PUSH2` | Place 2 byte item on stack |
| `62` | `PUSH3` | Place 3 byte item on stack |
| `63` | `PUSH4` | Place 4 byte item on stack |
| `64` | `PUSH5` | Place 5 byte item on stack |
| `65` | `PUSH6` | Place 6 byte item on stack |
| `66` | `PUSH7` | Place 7 byte item on stack |
| `67` | `PUSH8` | Place 8 byte item on stack |
| `68` | `PUSH9` | Place 9 byte item on stack |
| `69` | `PUSH10` | Place 10 byte item on stack |
| `6A` | `PUSH11` | Place 11 byte item on stack |
| `6B` | `PUSH12` | Place 12 byte item on stack |
| `6C` | `PUSH13` | Place 13 byte item on stack |
| `6D` | `PUSH14` | Place 14 byte item on stack |
| `6E` | `PUSH15` | Place 15 byte item on stack |
| `6F` | `PUSH16` | Place 16 byte item on stack |
| `70` | `PUSH17` | Place 17 byte item on stack |
| `71` | `PUSH18` | Place 18 byte item on stack |
| `72` | `PUSH19` | Place 19 byte item on stack |
| `73` | `PUSH20` | Place 20 byte item on stack |
| `74` | `PUSH21` | Place 21 byte item on stack |
| `75` | `PUSH22` | Place 22 byte item on stack |
| `76` | `PUSH23` | Place 23 byte item on stack |
| `77` | `PUSH24` | Place 24 byte item on stack |
| `78` | `PUSH25` | Place 25 byte item on stack |
| `79` | `PUSH26` | Place 26 byte item on stack |
| `7A` | `PUSH27` | Place 27 byte item on stack |
| `7B` | `PUSH28` | Place 28 byte item on stack |
| `7C` | `PUSH29` | Place 29 byte item on stack |
| `7D` | `PUSH30` | Place 30 byte item on stack|
| `7E` | `PUSH31` | Place 31 byte item on stack |
| `7F` | `PUSH32` | Place 32 byte (full word) item on stack |
| `80` | `DUP1` | Duplicate 1st stack item |
| `81` | `DUP2` | Duplicate 2nd stack item |
| `82` | `DUP3` | Duplicate 3rd stack item |
| `83` | `DUP4` | Duplicate 4th stack item |
| `84` | `DUP5` | Duplicate 5th stack item |
| `85` | `DUP6` | Duplicate 6th stack item |
| `86` | `DUP7` | Duplicate 7th stack item |
| `87` | `DUP8` | Duplicate 8th stack item |
| `88` | `DUP9` | Duplicate 9th stack item |
| `89` | `DUP10` | Duplicate 10th stack item |
| `8A` | `DUP11` | Duplicate 11th stack item |
| `8B` | `DUP12` | Duplicate 12th stack item |
| `8C` | `DUP13` | Duplicate 13th stack item |
| `8D` | `DUP14` | Duplicate 14th stack item |
| `8E` | `DUP15` | Duplicate 15th stack item |
| `8F` | `DUP16` | Duplicate 16th stack item |
| `90` | `SWAP1` | Exchange 1st and 2nd stack items |
| `91` | `SWAP2` | Exchange 1st and 3nd stack items |
| `92` | `SWAP3` | Exchange 1st and 4th stack items |
| `93` | `SWAP4` | Exchange 1st and 5th stack items |
| `94` | `SWAP5` | Exchange 1st and 6th stack items |
| `95` | `SWAP6` | Exchange 1st and 7th stack items |
| `96` | `SWAP7` | Exchange 1st and 8th stack items |
| `97` | `SWAP8` | Exchange 1st and 9th stack items |
| `98` | `SWAP9` | Exchange 1st and 10th stack items |
| `99` | `SWAP10` | Exchange 1st and 11th stack items |
| `9A` | `SWAP11` | Exchange 1st and 12nd stack items |
| `9B` | `SWAP12` | Exchange 1st and 13th stack items |
| `9C` | `SWAP13` |Exchange 1st and 14th stack items |
| `9D` | `SWAP14` | Exchange 1st and 15th stack items |
| `9E` | `SWAP15` | Exchange 1st and 16th stack items |
| `9F` | `SWAP16` | Exchange 1st and 17th stack items |
| `A0` | `LOG0` | Append log record with no topics |
| `A1` | `LOG1` | Append log record with one topic |
| `A2` | `LOG2` | Append log record with two topics |
| `A3` | `LOG3` | Append log record with three topics |
| `A4` | `LOG4` | Append log record with four topics |
| `F0` | `CREATE` | Create a new account with associated code |
| `F1` | `CALL` | Message-call into an account |
| `F2` | `CALLCODE` | Message-call into this account with alternative account’s code |
| `F3` | `RETURN` | Halt execution returning output data |
| `F4` | `DELEGATECALL` | Message-call into this account with an alternative account’s code, but persisting the current values for sender and value |
| `F5` | `CREATE2` | Create a new account with associated code at a predictable address |
| `FA` | `STATICCALL` | Static message-call into an account |
| `FD` | `REVERT` | Halt execution reverting state changes but returning data and remaining gas |
| `FE` | `INVALID` | Designated invalid instruction |
| `FF` | `SELFDESTRUCT` | Halt execution and register account for later deletion |
