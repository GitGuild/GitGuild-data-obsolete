# GCTM Asset Definition

CTM Guild Coins are claims against the CTM Guild Treasury. The usual way GCTM is created is by earning XP. GCTM are earned 1:1 with XP.

GCTM may be issued for reasons other than earning, without XP. For istance, GCTM issued as a reimbursement for expenses do not deserve XP. These cases are voted on individually.

### Roles

 + Member
 + Service Provider

All CTM Guild members are peers in the GCTM network. Any member may unilaterally transfer their GCTM to another by submitting a signed entry to the ledger. Members may redeem earned GCTM at a penalty of 1% per day from the day of the request, subject to fees and availability.

##### Member Withdrawal Table

To help explain the member withdrawals, this actuary table shows the expected yield assuming a hypothetical GWLT price of 1 chicken (CHKN).

| Days since request | Penalty | GCTM Redeemed | Yield |
|--------------------|---------|--------------|-------|
| 0 | 100% | 1 | 0 CHKN |
| 1 | 99% | 1 | 0.01 |
| 2 | 98% | 1 | 0.02 |
| 3 | 97% | 1 | 0.03 |
| n (< 100) | (100 - n)% | 1 | n / 100 |
| 100 | 0% | 1 | 1 |

Service Providers are outside of the CTM Guild, and unable to receive payment in GCTM. As such, they are not subject to time penalties, and may receive Treasury withdrawals immediately.

### Funds

Funds may be established by contract, to hold assets on behalf of the Treasury. These may elect cosigners to manage assets only with 90% approval, as per the Change Treasury Sign Policy.

Funds may charge up to 1% for withdrawal processing.

### Revenue

This guild will offer support and possibly other services to CTM operators. Details to be arranged in later contracts.

### Sponsorships

For every 1 non-sponsorship GCTM issued, an additional 1% GCTM will be issued and allocated to the Git Guild Treasury. For instance, if 2.2 GCTM are issued to a member, 0.022 GCTM are to be issued to the Git Guild Treasury.

##### Sponsorship Table

| Name | Recipient | Asset | Percent on Issue |
|------|-----------|-------|------------------|
| Git Guild | FX:GCTM:GitGuild | GCTM | 1% |
| TAPP Guild | FX:GCTM:TAPPGuild | GCTM | 4% |
| Wallet Guild | FX:GCTM:WalletGuild | GCTM | 10% |
| Trade Guild | FX:GCTM:TradeGuild | GCTM | 10% |
