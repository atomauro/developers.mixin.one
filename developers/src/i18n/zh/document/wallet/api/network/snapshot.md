### 转账详情

公开的转账详情，无需授权访问

### `GET /network/snapshots/:id` 

```
$$XIN:curl$$ "https://api.mixin.one/network/snapshots/8f5b244e-cf86-4374-8eaa-c551fd70cd83"
```

```json
{  
  "data":{  
    "amount":"-1688168",
      "asset":{
        "asset_id":"965e5c6e-434c-3fa9-b780-c50f43cd955c",
        "chain_id":"43d61dcd-e413-450d-80b8-101d5e903357",
        "icon_url":"https://images.mixin.one/0sQY63dDMkWTURkJVjowWY6Le4ICjAFuu3ANVyZA4uI3UdkbuOT5fjJUT82ArNYmZvVcxDXyNjxoOv0TAYbQTNKS=s128",
        "name":"Chui Niu Bi",
        "symbol":"CNB",
        "type":"asset"
      },
      "created_at":"2018-05-29T09:31:04.202186212Z",
      "data":"",
      "snapshot_id":"529934b0-abfd-43ab-9431-1805773000a4",
      // Includes DEPOSIT_CONFIRMED, TRANSFER_INITIALIZED, WITHDRAWAL_INITIALIZED, WITHDRAWAL_FEE_CHARGED, WITHDRAWAL_FAILED 
      "source":"TRANSFER_INITIALIZED",
      "type":"snapshot",
      // 如果需要对账查询所有钱包生成用户的转账，需要在请求头里附带钱包的认证鉴权信息，才会返回以下字段信息
      "user_id":"06aed1e3-bd77-4a59-991a-5bb5ae6fbb09",
      "trace_id":"7c67e8e8-b142-488b-80a3-61d4d29c90bf",
      "opponent_id":"a465ffdb-4441-4cb9-8b45-00cf79dfbc46",
      "data":"Transfer!"
  }
}
```