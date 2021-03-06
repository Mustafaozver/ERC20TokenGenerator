## SÅ«rya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| dist/BaseToken.dist.sol | 9af4a518aa2e38eed36a6d855e16c64b1a27258b |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     â      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **Context** | Implementation |  |||
| â | _msgSender | Internal ð |   | |
| â | _msgData | Internal ð |   | |
||||||
| **IERC20** | Interface |  |||
| â | totalSupply | External âï¸ |   |NOâï¸ |
| â | balanceOf | External âï¸ |   |NOâï¸ |
| â | transfer | External âï¸ | ð  |NOâï¸ |
| â | allowance | External âï¸ |   |NOâï¸ |
| â | approve | External âï¸ | ð  |NOâï¸ |
| â | transferFrom | External âï¸ | ð  |NOâï¸ |
||||||
| **SafeMath** | Library |  |||
| â | add | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | sub | Internal ð |   | |
| â | mul | Internal ð |   | |
| â | div | Internal ð |   | |
| â | div | Internal ð |   | |
| â | mod | Internal ð |   | |
| â | mod | Internal ð |   | |
||||||
| **Address** | Library |  |||
| â | isContract | Internal ð |   | |
| â | sendValue | Internal ð | ð  | |
| â | functionCall | Internal ð | ð  | |
| â | functionCall | Internal ð | ð  | |
| â | functionCallWithValue | Internal ð | ð  | |
| â | functionCallWithValue | Internal ð | ð  | |
| â | _functionCallWithValue | Private ð | ð  | |
||||||
| **ERC20** | Implementation | Context, IERC20 |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | name | Public âï¸ |   |NOâï¸ |
| â | symbol | Public âï¸ |   |NOâï¸ |
| â | decimals | Public âï¸ |   |NOâï¸ |
| â | totalSupply | Public âï¸ |   |NOâï¸ |
| â | balanceOf | Public âï¸ |   |NOâï¸ |
| â | transfer | Public âï¸ | ð  |NOâï¸ |
| â | allowance | Public âï¸ |   |NOâï¸ |
| â | approve | Public âï¸ | ð  |NOâï¸ |
| â | transferFrom | Public âï¸ | ð  |NOâï¸ |
| â | increaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | decreaseAllowance | Public âï¸ | ð  |NOâï¸ |
| â | _transfer | Internal ð | ð  | |
| â | _mint | Internal ð | ð  | |
| â | _burn | Internal ð | ð  | |
| â | _approve | Internal ð | ð  | |
| â | _setupDecimals | Internal ð | ð  | |
| â | _beforeTokenTransfer | Internal ð | ð  | |
||||||
| **ERC20Capped** | Implementation | ERC20 |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | cap | Public âï¸ |   |NOâï¸ |
| â | _beforeTokenTransfer | Internal ð | ð  | |
||||||
| **ERC20Burnable** | Implementation | Context, ERC20 |||
| â | burn | Public âï¸ | ð  |NOâï¸ |
| â | burnFrom | Public âï¸ | ð  |NOâï¸ |
||||||
| **IERC165** | Interface |  |||
| â | supportsInterface | External âï¸ |   |NOâï¸ |
||||||
| **IERC1363** | Interface | IERC20, IERC165 |||
| â | transferAndCall | External âï¸ | ð  |NOâï¸ |
| â | transferAndCall | External âï¸ | ð  |NOâï¸ |
| â | transferFromAndCall | External âï¸ | ð  |NOâï¸ |
| â | transferFromAndCall | External âï¸ | ð  |NOâï¸ |
| â | approveAndCall | External âï¸ | ð  |NOâï¸ |
| â | approveAndCall | External âï¸ | ð  |NOâï¸ |
||||||
| **IERC1363Receiver** | Interface |  |||
| â | onTransferReceived | External âï¸ | ð  |NOâï¸ |
||||||
| **IERC1363Spender** | Interface |  |||
| â | onApprovalReceived | External âï¸ | ð  |NOâï¸ |
||||||
| **ERC165Checker** | Library |  |||
| â | supportsERC165 | Internal ð |   | |
| â | supportsInterface | Internal ð |   | |
| â | supportsAllInterfaces | Internal ð |   | |
| â | _supportsERC165Interface | Private ð |   | |
| â | _callERC165SupportsInterface | Private ð |   | |
||||||
| **ERC165** | Implementation | IERC165 |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | supportsInterface | Public âï¸ |   |NOâï¸ |
| â | _registerInterface | Internal ð | ð  | |
||||||
| **ERC1363** | Implementation | ERC20, IERC1363, ERC165 |||
| â | <Constructor> | Public âï¸ | ð  | ERC20 |
| â | transferAndCall | Public âï¸ | ð  |NOâï¸ |
| â | transferAndCall | Public âï¸ | ð  |NOâï¸ |
| â | transferFromAndCall | Public âï¸ | ð  |NOâï¸ |
| â | transferFromAndCall | Public âï¸ | ð  |NOâï¸ |
| â | approveAndCall | Public âï¸ | ð  |NOâï¸ |
| â | approveAndCall | Public âï¸ | ð  |NOâï¸ |
| â | _checkAndCallTransfer | Internal ð | ð  | |
| â | _checkAndCallApprove | Internal ð | ð  | |
||||||
| **Ownable** | Implementation | Context |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
| â | owner | Public âï¸ |   |NOâï¸ |
| â | renounceOwnership | Public âï¸ | ð  | onlyOwner |
| â | transferOwnership | Public âï¸ | ð  | onlyOwner |
||||||
| **TokenRecover** | Implementation | Ownable |||
| â | recoverERC20 | Public âï¸ | ð  | onlyOwner |
||||||
| **EnumerableSet** | Library |  |||
| â | _add | Private ð | ð  | |
| â | _remove | Private ð | ð  | |
| â | _contains | Private ð |   | |
| â | _length | Private ð |   | |
| â | _at | Private ð |   | |
| â | add | Internal ð | ð  | |
| â | remove | Internal ð | ð  | |
| â | contains | Internal ð |   | |
| â | length | Internal ð |   | |
| â | at | Internal ð |   | |
| â | add | Internal ð | ð  | |
| â | remove | Internal ð | ð  | |
| â | contains | Internal ð |   | |
| â | length | Internal ð |   | |
| â | at | Internal ð |   | |
||||||
| **AccessControl** | Implementation | Context |||
| â | hasRole | Public âï¸ |   |NOâï¸ |
| â | getRoleMemberCount | Public âï¸ |   |NOâï¸ |
| â | getRoleMember | Public âï¸ |   |NOâï¸ |
| â | getRoleAdmin | Public âï¸ |   |NOâï¸ |
| â | grantRole | Public âï¸ | ð  |NOâï¸ |
| â | revokeRole | Public âï¸ | ð  |NOâï¸ |
| â | renounceRole | Public âï¸ | ð  |NOâï¸ |
| â | _setupRole | Internal ð | ð  | |
| â | _setRoleAdmin | Internal ð | ð  | |
| â | _grantRole | Private ð | ð  | |
| â | _revokeRole | Private ð | ð  | |
||||||
| **Roles** | Implementation | AccessControl |||
| â | <Constructor> | Public âï¸ | ð  |NOâï¸ |
||||||
| **ERC20Base** | Implementation | ERC20Capped, ERC20Burnable, ERC1363, Roles, TokenRecover |||
| â | <Constructor> | Public âï¸ | ð  | ERC20Capped ERC1363 |
| â | mintingFinished | Public âï¸ |   |NOâï¸ |
| â | transferEnabled | Public âï¸ |   |NOâï¸ |
| â | mint | Public âï¸ | ð  | canMint onlyMinter |
| â | transfer | Public âï¸ | ð  | canTransfer |
| â | transferFrom | Public âï¸ | ð  | canTransfer |
| â | finishMinting | Public âï¸ | ð  | canMint onlyOwner |
| â | enableTransfer | Public âï¸ | ð  | onlyOwner |
| â | _beforeTokenTransfer | Internal ð | ð  | |
||||||
| **BaseToken** | Implementation | ERC20Base |||
| â | <Constructor> | Public âï¸ | ð  | ERC20Base |
| â | generator | Public âï¸ |   |NOâï¸ |
| â | version | Public âï¸ |   |NOâï¸ |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    ð    | Function can modify state |
|    ðµ    | Function is payable |
