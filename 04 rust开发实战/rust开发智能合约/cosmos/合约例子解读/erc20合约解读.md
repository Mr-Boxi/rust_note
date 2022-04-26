分别从cosmwasm合约的三个入口点阅读一个合约。

## erc20 前置知识

...

## 实例化 Instantiate

### InstantiateMsg

```rust
// 实例化的相关消息
#[derive(Serialize, Deserialize, JsonSchema)]
```



```rust
// contract.rs
fn instantiate(
	deps: DepsMut,
    _env: Env,
    _info: MessageInfo,
    msg: InstantiateMsg,
) -> Result<Response, ContractError>{
    
}
```

## 执行 (Execute)



## 查询(Query)

