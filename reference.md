# Reference

## Export

<details><summary><code>client.export.<a href="/src/api/resources/export/client/Client.ts">getCmcStats</a>() -> Record<string, Stonfi.CmcPoolStats>[]</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.export.getCmcStats();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `Export.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.export.<a href="/src/api/resources/export/client/Client.ts">screenerAssetInfo</a>(address) -> Stonfi.ScreenerAssetInfoResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.export.screenerAssetInfo("address");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**address:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Export.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.export.<a href="/src/api/resources/export/client/Client.ts">screenerEvents</a>({ ...params }) -> Stonfi.ScreenerEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.export.screenerEvents({
    fromBlock: 1,
    toBlock: 1,
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.ScreenerEventsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Export.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.export.<a href="/src/api/resources/export/client/Client.ts">screenerLatestBlock</a>() -> Stonfi.ScreenerLatestBlockResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.export.screenerLatestBlock();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `Export.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.export.<a href="/src/api/resources/export/client/Client.ts">screenerPoolInfo</a>(address) -> Stonfi.ScreenerPoolInfoResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.export.screenerPoolInfo("address");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**address:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Export.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Dex

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getAssetList</a>() -> Stonfi.GetAssetListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getAssetList();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">assetQuery</a>({ ...params }) -> Stonfi.AssetQueryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.assetQuery();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.AssetQueryRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">assetSearch</a>({ ...params }) -> Stonfi.AssetSearchResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.assetSearch({
    search_string: "search_string",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.AssetSearchRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getAsset</a>(addrStr) -> Stonfi.GetAssetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getAsset("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getFarmList</a>({ ...params }) -> Stonfi.GetFarmListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getFarmList();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetFarmListRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getFarmsByPool</a>(poolAddrStr) -> Stonfi.GetFarmsByPoolResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getFarmsByPool("pool_addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**poolAddrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getFarm</a>(addrStr) -> Stonfi.GetFarmResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getFarm("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">simulateLiquidityProvision</a>({ ...params }) -> Stonfi.DexSimulateLiquidityProvisionResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.simulateLiquidityProvision({
    provision_type: "Initial",
    pool_address: "EQCGScrZe1xbyWqWDvdI6mzP-GAcAWFv6ZXuaJOuSqemxku4",
    wallet_address: "UQDYzZmfsrGzhObKJUw4gzdeIxEai3jAFbiGKGwxvxHinf4K",
    token_a: "EQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAM9c",
    token_b: "EQCxE6mUtQJKFnGfaROTKOt1lZbDiiX1kCixRv7Nw2Id_sDs",
    token_a_units: "10",
    token_b_units: "10",
    slippage_tolerance: "0.001",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.DexSimulateLiquidityProvisionRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getMarketList</a>({ ...params }) -> Stonfi.GetMarketListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getMarketList();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetMarketListRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">poolQuery</a>({ ...params }) -> Stonfi.PoolQueryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.poolQuery();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.PoolQueryRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getPoolList</a>({ ...params }) -> Stonfi.GetPoolListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getPoolList();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetPoolListRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getPoolListByMarket</a>(asset0AddrStr, asset1AddrStr) -> Stonfi.GetPoolListByMarketResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getPoolListByMarket("asset_0_addr_str", "asset_1_addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**asset0AddrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**asset1AddrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getPool</a>(addrStr) -> Stonfi.GetPoolResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getPool("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">reverseSimulateSwapUtoipa</a>({ ...params }) -> Stonfi.DexReverseSimulateSwapUtoipaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.reverseSimulateSwapUtoipa({
    offer_address: "EQBynBO23ywHy_CgarY9NK9FTz0yDsG82PtcbSTQgGoXwiuA",
    ask_address: "EQCM3B12QK1e4yZSf8GtBRT0aLMNyEsBc_DhVfRRtOEffLez",
    units: "300",
    slippage_tolerance: "0.001",
    pool_address: "EQAKleHU6-eGDQUfi4YXMNve4UQP0RGAIRkU4AiRRlgDUbaM",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.DexReverseSimulateSwapUtoipaRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getRouterList</a>({ ...params }) -> Stonfi.GetRouterListResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getRouterList();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetRouterListRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">getRouter</a>(addrStr) -> Stonfi.GetRouterResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.getRouter("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">simulateSwapUtoipa</a>({ ...params }) -> Stonfi.DexSimulateSwapUtoipaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.simulateSwapUtoipa({
    offer_address: "EQBynBO23ywHy_CgarY9NK9FTz0yDsG82PtcbSTQgGoXwiuA",
    ask_address: "EQCM3B12QK1e4yZSf8GtBRT0aLMNyEsBc_DhVfRRtOEffLez",
    units: "300",
    slippage_tolerance: "0.001",
    pool_address: "EQAKleHU6-eGDQUfi4YXMNve4UQP0RGAIRkU4AiRRlgDUbaM",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.DexSimulateSwapUtoipaRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.dex.<a href="/src/api/resources/dex/client/Client.ts">swapStatus</a>({ ...params }) -> Stonfi.DexSwapStatusResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.dex.swapStatus({
    router_address: "EQB3ncyBUTjZUA5EnFKR5_EnOMI9V1tTEAAPaiU71gc4TiUt",
    owner_address: "EQCM3B12QK1e4yZSf8GtBRT0aLMNyEsBc_DhVfRRtOEffLez",
    query_id: "1",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.DexSwapStatusRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Dex.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Jetton

<details><summary><code>client.jetton.<a href="/src/api/resources/jetton/client/Client.ts">getWalletAddress</a>(addrStr, { ...params }) -> Stonfi.GetWalletAddressResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.jetton.getWalletAddress("addr_str", {
    owner_address: "EQCM3B12QK1e4yZSf8GtBRT0aLMNyEsBc_DhVfRRtOEffLez",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `Stonfi.GetWalletAddressRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Jetton.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Stats

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getDexStats</a>({ ...params }) -> Stonfi.GetDexStatsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getDexStats({
    since: "2023-06-01T12:34:56",
    until: "2023-06-02T23:59:59",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetDexStatsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getFeeAccrualsStats</a>({ ...params }) -> Stonfi.GetFeeAccrualsStatsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getFeeAccrualsStats({
    referrer_address: "EQCwiRZrfUSlMM0dz-Hm4KW1IqaFz1Pwxg3-t0jQDt36qOar",
    since: "2025-04-01T12:00:00",
    until: "2025-04-03T13:00:00",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetFeeAccrualsStatsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getFeeWithdrawalsStats</a>({ ...params }) -> Stonfi.GetFeeWithdrawalsStatsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getFeeWithdrawalsStats({
    referrer_address: "EQCwiRZrfUSlMM0dz-Hm4KW1IqaFz1Pwxg3-t0jQDt36qOar",
    since: "2025-04-01T12:00:00",
    until: "2025-04-03T13:00:00",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetFeeWithdrawalsStatsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getFeesStats</a>({ ...params }) -> Stonfi.GetFeesStatsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Queries the list operations in specified time range that lead to fee accruals to specified referrer

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getFeesStats({
    referrer_address: "EQCwiRZrfUSlMM0dz-Hm4KW1IqaFz1Pwxg3-t0jQDt36qOar",
    since: "2025-04-01T12:00:00",
    until: "2025-04-03T13:00:00",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetFeesStatsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getOperationStatsUtoipa</a>({ ...params }) -> Stonfi.GetOperationStatsUtoipaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getOperationStatsUtoipa({
    since: "2023-06-01T12:34:56",
    until: "2023-06-02T23:59:59",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetOperationStatsUtoipaRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getPoolStatsUtoipa</a>({ ...params }) -> Stonfi.GetPoolStatsUtoipaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getPoolStatsUtoipa({
    since: "2023-06-01T12:34:56",
    until: "2023-06-02T23:59:59",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `Stonfi.GetPoolStatsUtoipaRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.stats.<a href="/src/api/resources/stats/client/Client.ts">getStakingStats</a>() -> Stonfi.GetStakingStatsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.stats.getStakingStats();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `Stats.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## Wallets

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletAssets</a>(addrStr) -> Stonfi.GetWalletAssetsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletAssets("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletAsset</a>(addrStr, assetStr) -> Stonfi.GetWalletAssetResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletAsset("addr_str", "asset_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**assetStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletFarms</a>(addrStr, { ...params }) -> Stonfi.GetWalletFarmsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletFarms("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `Stonfi.GetWalletFarmsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletFarm</a>(addrStr, farmStr) -> Stonfi.GetWalletFarmResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletFarm("addr_str", "farm_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**farmStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getFeeVaults</a>(addrStr) -> Stonfi.GetFeeVaultsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getFeeVaults("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletOperationsUtoipa</a>(addrStr, { ...params }) -> Stonfi.GetWalletOperationsUtoipaResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletOperationsUtoipa("addr_str", {
    since: "2023-06-01T12:34:56",
    until: "2023-06-02T23:59:59",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `Stonfi.GetWalletOperationsUtoipaRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletPools</a>(addrStr, { ...params }) -> Stonfi.GetWalletPoolsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletPools("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**request:** `Stonfi.GetWalletPoolsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletPool</a>(addrStr, poolStr) -> Stonfi.GetWalletPoolResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletPool("addr_str", "pool_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**poolStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.wallets.<a href="/src/api/resources/wallets/client/Client.ts">getWalletStakes</a>(addrStr) -> Stonfi.GetWalletStakesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.wallets.getWalletStakes("addr_str");
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**addrStr:** `string`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Wallets.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>
